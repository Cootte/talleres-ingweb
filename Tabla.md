Titulo
=====

|REQ/RES           |Método HTTP (solo REQ)     |       URL| Headers (sólo nombres)      |Status(solo RES)   |    Descripción    |
| -- | -- | -- | -- | -- | -- |
| 1.REQ | Get |http://zeus.inf.ucv.cl/~ifigueroa/doku.php  |Host,Upgrade-Insecure-Requests,User-Agent,Accept,Acept Endconding| n/a | -- |
| 2.RES | n/a | n/a | Date,Server,Expires,Cache-Control,Pragma,X-UA-Compatible,Content-Encoding,Content-Length,Keep-Alive,Connection, Content-Type, charset| 200 | Se devuelve correctamente el sitio. Al parecer no se encontró en algún caché, lo que gatilló algunas operaciones lookup. |
| 3.REQ | Get |ttp://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/bootstrap/default/bootstrap.min.css  |Host,User-Agent,Accept, Acccept Endconding| n/a | --|
| 4.RES | n/a | n/a | Date,Server,Last-Modified,ETag,Accept-Ranges,Content-Encoding,Content-Length,Content-Type| 200 |  |
| 5.REQ | Get |http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/css.php?t=bootstrap3&tseed=44b1422730da0b8e0624124cac9afe4b  |Host,Upgrade-Insecure-Requests,User-Agent,Accept,Acept Endconding| n/a | -- |
| 6.RES | n/a | n/a | Date,Server,X-Powered-By,Cache-Control,Pragma,ETag,Last-Modified,Content-Encoding,Content-Length,Content-Type| 200 |  |
| 7.REQ | Get |http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/font-awesome/css/font-awesome.min.css |Host,User-Agent,Accept,Acept Endconding| n/a | -- |
| 8.RES | n/a | n/a | Date,Server,Last-Modified,ETag,Accept-Ranges,Content-Encoding,Content-Length,Content-Type| 200 |  |
| 9.REQ | Get |http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/indexer.php?id=start&1554338182 |Accept,Acept Endconding| n/a | -- |
| 10.RES | n/a | n/a | Date,Server,X-Powered-By,Expires,Cache-Control,Pragma,Connection,Content-Length,Content-Typef| 200 |  |
