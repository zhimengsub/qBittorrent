把制作种子工具暴露到命令行

命令格式（可根据实际情况调整）：

`qbittorrent.exe --make <SOURCE> [--output=OUTPUT] [--silent] [--auto-seed=<true|false>] [--tracker-list=<filepath>]`

- Make torrent
- -m, --make: Make torrent
- SOURCE: Source directory or source file of which to make the torrent (absolute path supported).
- -o, --output: (optional) target location. Leaving this blank means using the same path as the source directory or file, for saving the generated torrent.
- OUTPUT: path for the generated .torrent file (only absolute path supported).
- -s, --silent: (optional) start task in silent mode. Automatically make torrent with default parameters without confirmation.（命令行提供的参数覆盖掉默认参数）
- --auto-seed: (optional, default=true): 制作完成后开始做种
- --tracker-list: (optional): 提供tracker列表（txt文件，每行是一个url，注意处理换行符和空行）

Optional：添加使用说明到-h窗口里
