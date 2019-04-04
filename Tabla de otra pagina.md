|REQ/RES           |Método HTTP (solo REQ)     |       URL| Headers (sólo nombres)      |Status(solo RES)   |    Descripción    |
| -- | -- | --- | -- | -- | -- |
| 1.REQ  | GET  |  https://www.facebook.com   |  Origin, User-Agent,Content-Type,Accept    | n/a  |   |
|2.RES|n/a| n/a |content-encoding,content-type,x-frame-options,expires,strict-transport-security,expect-ct,access-control-expose-headers,access-control-allow-credentials,x-content-type-options,access-control-allow-origin,access-control-allow-methods,x-fb-debug,date |200 | |
|3.REQ|GET|https://static.xx.fbcdn.net/rsrc.php/v3/yQ/r/P7iQUKoCRnx.png |User-Agent,Accept |n/a||
|4.RES|n/a|n/a|content-type,x-content-type-option,timing-allow-origin,access-control-allow-origin,content-md5,cache-control,x-fb-debug,content-length|200||
|5.REQ|GET|https://scontent-scl1-1.xx.fbcdn.net/v/t1.0-1/c1.0.130.130a/p130x130/19642399_10213076829933566_8485362265789054306_n.jpg?_nc_cat=111&_nc_ht=scontent-scl1-1.xx&oh=49db26527ff17689ebff171bf35f16c8&oe=5D3F1B74 |User-Agent,Accept|n/a||
|6.RES|n/a|n/a|last-modified,x-haystack-needlechecksum,x-needle-checksum,content-type,x-fb-config-version-olb-prod,timing-allow-origin,access-control-allow-origin,cache-control,content-length,x-fb-config-version-elb-prod,date,x-fb-edge-debug,access-control-expose-headers|200||
|7.REQ|GET|https://scontent-scl1-1.xx.fbcdn.net/v/t1.0-1/c0.22.130.130a/p130x130/52783833_262394061320348_1919901723351056384_n.jpg?_nc_cat=111&_nc_ht=scontent-scl1-1.xx&oh=e449d08e040e9d8ae23ae30891fd1d8a&oe=5D0B17F6 |User-Agent,Accept|n/a||
|8.RES|n/a|n/a|last-modified,x-haystack-needlechecksum,x-needle-checksum,content-type,x-fb-config-version-olb-prod,timing-allow-origin,access-control-allow-origin,cache-control,content-length,datemaccess-control-expose-headers|200||
|9.REQ|GET|https://scontent-scl1-1.xx.fbcdn.net/v/t1.0-1/p130x130/12670648_448986065311702_2474186993469468691_n.jpg?_nc_cat=103&_nc_ht=scontent-scl1-1.xx&oh=0d5d15853e7edd42569c72ef48a02e92&oe=5D0877A0 |User-Agent,Accept|n/a||
|10.RES|n/a|n/a|last-modified,x-haystack-needlechecksum,x-needle-checksum,content-type,x-fb-config-version-olb-prod,-fb-config-version-olb-prod,access-control-allow-origin,cache-control,content-length,x-fb-config-version-elb-prod,date,access-control|200||
