Flume connector
=======

These files are created by thrift 1.0.0 and the Flume version we tested is 1.6.0. If different verions of Flume and Thrift are used, new connector files can be generated by the following command:

    thrift -r --gen cpp $FLUME_SRC_HOME/flume-ng-sdk/src/main/thrift/flume.thrift

$FLUME_SRC_HOME indicates the root directory of Apache Flume source. After typeing the above command, new connector files will be generated under ./gen-cpp/. We then can replace the connector files with the new files. 


