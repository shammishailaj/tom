## tom invoice

Create a new invoice in a cloud based service. See the list of command to see which service APIs are supported at this time.

### Synopsis

Create a new invoice in a cloud based service. See the list of command to see which service APIs are supported at this time.

### Options

```
  -d, --dry-run                    Dry run without creating data on the remote side
  -h, --help                       help for invoice
      --month int                  The month to list in the reporting. Default: -1 (last month) (default -1)
  -p, --project string             Project to list in the invoice.
      --round-frames string        Rounding mode for time frames of the projects. Default: up (always round up) (default "up")
      --round-frames-to duration   Round frames to multiples of this duration. Default: 0 (no rounding)
```

### Options inherited from parent commands

```
  -c, --config string     config file (default is $HOME/.gotime.yaml)
      --data-dir string   data directory (default is $HOME/.gotime)
```

### SEE ALSO

* [tom](tom.md)	 - tom is a command line application to track time.
* [tom invoice sevdesk](tom_invoice_sevdesk.md)	 - Create a new invoice at sevdesk.com

###### Auto generated by spf13/cobra on 7-Jan-2019