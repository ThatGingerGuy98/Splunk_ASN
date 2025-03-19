Adds a lookup table named "asn_reference"
Example query below to get started
```<base search> | lookup asn_reference Range AS RemoteAddress OUTPUT Owner | table RemoteAddress Owner ```
