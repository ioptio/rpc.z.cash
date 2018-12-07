#### getblockhash
```
getblockhash index
```

{% assign summary_getblockhash="Returns the hash of a block from the best (longest) blockchain at the index provided." %}

{{summary_getblockhash}}

Arguments:
```
1. index         (numeric, required) The block index
```

Result:
```
"hash"         (string) The block hash
```

*Example:* 
```bash
$ zcash-cli getblockhash 440296 
```

*Result:*
```
000000000271d725a541a3366a682e782a9a178583030ab0234ab3788447f692
```

*Example (cURL):*
```bash
$ curl --user username --data-binary '{"jsonrpc": "1.0", "id":"curltest", "method": "getblockhash", "params": [440296] }' -H 'content-type: text/plain;' http://127.0.0.1:8232/
```

*Result (cURL):*
```json
{"result":"000000000271d725a541a3366a682e782a9a178583030ab0234ab3788447f692","error":null,"id":"curltest"}
```

See also:

* [GetBlock](#getblock)
* [GetBestBlockHash](#getbestblockhash)

