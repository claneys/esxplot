# Usage

```bash
USAGE: esxplot -c 'Group Cpu' -f esx.csv
  -c REGEXP           category regexp pattern
  -m METRIC_REGEXP    metric pattern to find, could be coupled with -v to precise on
                      which VM.
  -v VM               pattern to search for, could be coupled with -m to filter on
                      metrics
  -f FILE             csv file to parse. Could be specified several times, which will
                      aggregate the metric for the files specified into one graph.
  -s SIZE             size in format x,y (ie: 640,480) to apply to the output.
                      Default to 1024,768
  -o OUTPUT_NAME      output file name without the extension.  -S
  [COLUMN|VM|METRIC|FILE] sort by VM or metric or ESX (aka file)
  -h help
  ```
