---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

{% assign table_name="Name" %}
{% assign table_type="Type" %}
{% assign table_Presence="Presence" %}
{% assign table_type="Description" %}

## Zcash RPC

The official Zcash client, zcashd, provides a remote procedure call (RPC) interface for various administrative tasks, wallet operations, and queries about network and blockchain data.

### Quick Reference
#### Blockchain
* [GetBlock](#getblock) {{summary_getblock}}
* [GetBestBlockHash](#getbestblockhash) {{summary_getbestblockhash}}
* [GetBlockHash](#getblockhash) {{summary_getblockhash}}

### Blockchain
{% include getbestblockhash.md %}
{% include getblock.md %}
{% include getblockhash.md %}
