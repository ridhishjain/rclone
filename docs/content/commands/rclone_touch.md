---
date: 2020-02-10T12:28:36Z
title: "rclone touch"
slug: rclone_touch
url: /commands/rclone_touch/
# autogenerated - DO NOT EDIT, instead edit the source code in cmd/touch/ and as part of making a release run "make commanddocs"
---
## rclone touch

Create new file or change file modification time.

### Synopsis

Create new file or change file modification time.

```
rclone touch remote:path [flags]
```

### Options

```
  -h, --help               help for touch
  -C, --no-create          Do not create the file if it does not exist.
  -t, --timestamp string   Change the modification times to the specified time instead of the current time of day. The argument is of the form 'YYMMDD' (ex. 17.10.30) or 'YYYY-MM-DDTHH:MM:SS' (ex. 2006-01-02T15:04:05)
```

See the [global flags page](/flags/) for global options not listed here.

### SEE ALSO

* [rclone](/commands/rclone/)	 - Show help for rclone commands, flags and backends.

