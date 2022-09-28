# kradicale_index

Storage extension for [Radicale](https://github.com/Kozea/Radicale) that optimizes reporting using a sqlite index.

## Configuration

Change the storage in your `config` file and set which fields should be indexed:

```ini
...

[storage]
type = kradicale_storage_index
kradicale_storage_index_fields = dtstart, dtend, uid, summary

```

