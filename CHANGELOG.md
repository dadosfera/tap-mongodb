# Changelog

## 0.1.2
  * Encode bytes back to base64 strings as we do not know the encodings [#13](https://github.com/singer-io/tap-mongodb/pull/13)

## 0.1.1
  * During key-based incremental sync, if replication-key changes, wipe state and resync table [#10](https://github.com/singer-io/tap-mongodb/pull/10)
  * Only support replication keys of types `datetime`, `timestamp`, `integer`, `ObjectId` [#10](https://github.com/singer-io/tap-mongodb/pull/10)
  * Only discover databases the user has read access for [#11](https://github.com/singer-io/tap-mongodb/pull/11)

## 0.1.0
 * Added key-based incremental sync [commit](https://github.com/singer-io/tap-mongodb/commit/b618b11d91e111680f70b402c6e94c9bf40c7b8f)
 
## 0.0.5
 * Fixed bug in oplog projections [commit](https://github.com/singer-io/tap-mongodb/commit/b400836678440499d4a15fb7d5b0a40a13e3342e)

## 0.0.4
 * Fixed bug in oplog projections [commit](https://github.com/singer-io/tap-mongodb/commit/527287e69661e9dbce3f05696b269025d0fc4034)
 * Added metric log printout at end of tap run [commit](https://github.com/singer-io/tap-mongodb/commit/d0403d82028b1dcc9ba306b52b2103ef00188b7d)