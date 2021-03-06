
<!---
# Licensed to the Apache Software Foundation (ASF) under one
# or more contributor license agreements.  See the NOTICE file
# distributed with this work for additional information
# regarding copyright ownership.  The ASF licenses this file
# to you under the Apache License, Version 2.0 (the
# "License"); you may not use this file except in compliance
# with the License.  You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
-->
# Apache Hadoop Changelog

## Release 0.13.0 - 2007-06-08

### INCOMPATIBLE CHANGES:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |


### IMPORTANT ISSUES:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |


### NEW FEATURES:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |
| [HADOOP-1251](https://issues.apache.org/jira/browse/HADOOP-1251) | A method to get the InputSplit from a Mapper |  Major | . | Owen O'Malley | Owen O'Malley |
| [HADOOP-1247](https://issues.apache.org/jira/browse/HADOOP-1247) | Make Hadoop Abacus work with Hadoop Streaming |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1217](https://issues.apache.org/jira/browse/HADOOP-1217) | Specify a junit test timeout in build.xml files |  Minor | build | Nigel Daley | Nigel Daley |
| [HADOOP-1216](https://issues.apache.org/jira/browse/HADOOP-1216) | Hadoop should support reduce none option |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1120](https://issues.apache.org/jira/browse/HADOOP-1120) | Contribute some code helping implement map/reduce apps for joining data from multiple sources |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1111](https://issues.apache.org/jira/browse/HADOOP-1111) | Job completion notification to a job configured URL |  Major | . | Alejandro Abdelnur |  |
| [HADOOP-702](https://issues.apache.org/jira/browse/HADOOP-702) | DFS Upgrade Proposal |  Major | . | Konstantin Shvachko | Konstantin Shvachko |
| [HADOOP-485](https://issues.apache.org/jira/browse/HADOOP-485) | allow a different comparator for grouping keys in calls to reduce |  Major | . | Owen O'Malley | Tahir Hashmi |


### IMPROVEMENTS:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |
| [HADOOP-1326](https://issues.apache.org/jira/browse/HADOOP-1326) | Return the RunningJob from JobClient.runJob |  Major | . | Owen O'Malley | Owen O'Malley |
| [HADOOP-1324](https://issues.apache.org/jira/browse/HADOOP-1324) | FSError encountered by one running task should not be fatal to other tasks on that node |  Major | . | Devaraj Das | Arun C Murthy |
| [HADOOP-1315](https://issues.apache.org/jira/browse/HADOOP-1315) | Hadoop Streaming code clean up |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1308](https://issues.apache.org/jira/browse/HADOOP-1308) | Tighten generic Class restrictions in JobConf.java |  Minor | . | Michael Bieniosek | Michael Bieniosek |
| [HADOOP-1304](https://issues.apache.org/jira/browse/HADOOP-1304) | MAX\_TASK\_FAILURES should be configurable |  Major | . | Christian Kunz | Devaraj Das |
| [HADOOP-1290](https://issues.apache.org/jira/browse/HADOOP-1290) | Move Hadoop Abacus to hadoop.mapred.lib |  Major | . | Runping Qi |  |
| [HADOOP-1284](https://issues.apache.org/jira/browse/HADOOP-1284) | clean up the protocol between stream mapper/reducer and the framework |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1276](https://issues.apache.org/jira/browse/HADOOP-1276) | TaskTracker expiry interval is not configurable |  Major | . | Alejandro Abdelnur | Arun C Murthy |
| [HADOOP-1270](https://issues.apache.org/jira/browse/HADOOP-1270) | Randomize the fetch of map outputs |  Major | . | Arun C Murthy | Arun C Murthy |
| [HADOOP-1263](https://issues.apache.org/jira/browse/HADOOP-1263) | retry logic when dfs exist or open fails temporarily, e.g because of timeout |  Major | . | Christian Kunz | Hairong Kuang |
| [HADOOP-1260](https://issues.apache.org/jira/browse/HADOOP-1260) | need code review guidelines |  Major | build | Nigel Daley | Nigel Daley |
| [HADOOP-1250](https://issues.apache.org/jira/browse/HADOOP-1250) | Remove the MustangFile class from streaming and promote the chmod into FileUtils |  Major | . | Owen O'Malley | Owen O'Malley |
| [HADOOP-1214](https://issues.apache.org/jira/browse/HADOOP-1214) | the first step for streaming clean up |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1213](https://issues.apache.org/jira/browse/HADOOP-1213) | When RPC call fails then log call message detail |  Minor | ipc | Nigel Daley | Doug Cutting |
| [HADOOP-1194](https://issues.apache.org/jira/browse/HADOOP-1194) | map output should not do block level compression |  Major | . | Runping Qi | Arun C Murthy |
| [HADOOP-1190](https://issues.apache.org/jira/browse/HADOOP-1190) | Fix unchecked warnings |  Major | . | Tom White | Tom White |
| [HADOOP-1167](https://issues.apache.org/jira/browse/HADOOP-1167) | InMemoryFileSystem uses synchronizedtMaps with maps that are locked anyways |  Minor | fs | Owen O'Malley | Owen O'Malley |
| [HADOOP-1166](https://issues.apache.org/jira/browse/HADOOP-1166) | Pull the NullOutputFormat into the lib package |  Major | . | Owen O'Malley | Owen O'Malley |
| [HADOOP-1165](https://issues.apache.org/jira/browse/HADOOP-1165) | Code for toString in code generated by Record I/O Compiler can be generic |  Minor | record | Milind Bhandarkar | Milind Bhandarkar |
| [HADOOP-1161](https://issues.apache.org/jira/browse/HADOOP-1161) | need improved release process |  Major | build | Doug Cutting | Doug Cutting |
| [HADOOP-1148](https://issues.apache.org/jira/browse/HADOOP-1148) | re-indent all code |  Minor | . | Doug Cutting | Doug Cutting |
| [HADOOP-1144](https://issues.apache.org/jira/browse/HADOOP-1144) | Hadoop should allow a configurable percentage of failed map tasks before declaring a job failed. |  Major | . | Christian Kunz | Arun C Murthy |
| [HADOOP-1133](https://issues.apache.org/jira/browse/HADOOP-1133) | Tools to analyze and debug namenode on a production cluster |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1131](https://issues.apache.org/jira/browse/HADOOP-1131) | Add a closeAll() static method to FileSystem |  Minor | . | Philippe Gassmann |  |
| [HADOOP-1127](https://issues.apache.org/jira/browse/HADOOP-1127) | Speculative Execution and output of Reduce tasks |  Major | . | Arun C Murthy | Arun C Murthy |
| [HADOOP-1116](https://issues.apache.org/jira/browse/HADOOP-1116) | Add maxmemory="256m" in the junit call of build-contrib.xml |  Major | build | Philippe Gassmann |  |
| [HADOOP-1101](https://issues.apache.org/jira/browse/HADOOP-1101) | Add more statistics in the web-ui to do with tasks |  Major | . | Devaraj Das | Devaraj Das |
| [HADOOP-1094](https://issues.apache.org/jira/browse/HADOOP-1094) | Optimize readFields and write methods in record I/O |  Major | record | Milind Bhandarkar | Milind Bhandarkar |
| [HADOOP-1068](https://issues.apache.org/jira/browse/HADOOP-1068) | Improve error message for 0 datanode case |  Major | . | Owen O'Malley | dhruba borthakur |
| [HADOOP-988](https://issues.apache.org/jira/browse/HADOOP-988) | Namenode should use single map for block to its meta data. |  Major | . | Raghu Angadi | Raghu Angadi |
| [HADOOP-978](https://issues.apache.org/jira/browse/HADOOP-978) | AlreadyBeingCreatedException detail message could contain more useful info |  Minor | . | Nigel Daley | Konstantin Shvachko |
| [HADOOP-971](https://issues.apache.org/jira/browse/HADOOP-971) | DFS Scalabilty: Improve name node performance by adding a hostname to datanodes map |  Major | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-968](https://issues.apache.org/jira/browse/HADOOP-968) | Reduce shuffle and merge should be done a child JVM |  Major | . | Owen O'Malley | Devaraj Das |
| [HADOOP-819](https://issues.apache.org/jira/browse/HADOOP-819) | LineRecordWriter should not always insert tab char between key and value |  Major | . | Runping Qi | Runping Qi |


### BUG FIXES:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |
| [HADOOP-1452](https://issues.apache.org/jira/browse/HADOOP-1452) | map output transfers of more than 2^31 bytes output are failing |  Blocker | . | Christian Kunz | Owen O'Malley |
| [HADOOP-1435](https://issues.apache.org/jira/browse/HADOOP-1435) | FileSystem.globPaths should not create a Path from an empty string |  Blocker | fs | Hairong Kuang | Hairong Kuang |
| [HADOOP-1431](https://issues.apache.org/jira/browse/HADOOP-1431) | Map tasks can't timeout for failing to call progress |  Blocker | . | Owen O'Malley | Arun C Murthy |
| [HADOOP-1427](https://issues.apache.org/jira/browse/HADOOP-1427) | Typo in GzipCodec.createInputStream - bufferSize |  Blocker | io | Espen Amble Kolstad | Espen Amble Kolstad |
| [HADOOP-1411](https://issues.apache.org/jira/browse/HADOOP-1411) | AlreadyBeingCreatedException from task retries |  Blocker | . | Nigel Daley | Hairong Kuang |
| [HADOOP-1407](https://issues.apache.org/jira/browse/HADOOP-1407) | Failed tasks not killing job |  Blocker | . | Nigel Daley | Arun C Murthy |
| [HADOOP-1388](https://issues.apache.org/jira/browse/HADOOP-1388) | Possible Null Pointer Dereference in taskdetails.jsp |  Major | . | Devaraj Das | Devaraj Das |
| [HADOOP-1386](https://issues.apache.org/jira/browse/HADOOP-1386) | The constructor of Path should not take an empty string as a parameter |  Blocker | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1385](https://issues.apache.org/jira/browse/HADOOP-1385) | MD5Hash has a bad hash function |  Major | io | Owen O'Malley | Owen O'Malley |
| [HADOOP-1369](https://issues.apache.org/jira/browse/HADOOP-1369) | Inconsistent synchronization of TaskTracker fields |  Blocker | . | Nigel Daley | Owen O'Malley |
| [HADOOP-1368](https://issues.apache.org/jira/browse/HADOOP-1368) | Inconsistent synchronization of 3 fields in JobInProgress.java |  Blocker | . | Nigel Daley | Owen O'Malley |
| [HADOOP-1363](https://issues.apache.org/jira/browse/HADOOP-1363) | waitForCompletion() calls Thread.sleep() with a lock held |  Blocker | . | Nigel Daley | Owen O'Malley |
| [HADOOP-1361](https://issues.apache.org/jira/browse/HADOOP-1361) | seek calls in 3 io classes ignore result of skipBytes(int) |  Blocker | io | Nigel Daley | Hairong Kuang |
| [HADOOP-1358](https://issues.apache.org/jira/browse/HADOOP-1358) | seek call ignores result of skipBytes(int) |  Blocker | . | Nigel Daley | Hairong Kuang |
| [HADOOP-1356](https://issues.apache.org/jira/browse/HADOOP-1356) | ValueHistogram.addNextValue(Object) ignores return value of String.substring(int, int) |  Blocker | . | Nigel Daley | Runping Qi |
| [HADOOP-1354](https://issues.apache.org/jira/browse/HADOOP-1354) | Null pointer dereference of paths in FsShell.dus(String) |  Blocker | fs | Nigel Daley | Hairong Kuang |
| [HADOOP-1353](https://issues.apache.org/jira/browse/HADOOP-1353) | Null pointer dereference of nodeInfo in FSNamesystem.removeDatanode(DatanodeID) |  Blocker | . | Nigel Daley | dhruba borthakur |
| [HADOOP-1350](https://issues.apache.org/jira/browse/HADOOP-1350) | Shuffle started taking a very long time after the HADOOP-1176 fix |  Blocker | . | Devaraj Das | Devaraj Das |
| [HADOOP-1345](https://issues.apache.org/jira/browse/HADOOP-1345) | Checksum object does not get restored to the old state in retries when handle ChecksumException |  Blocker | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1332](https://issues.apache.org/jira/browse/HADOOP-1332) | Sporadic unit test failures (TestMiniMRClasspath, TestMiniMRLocalFS, TestMiniMRDFSCaching) |  Blocker | . | Nigel Daley | Arun C Murthy |
| [HADOOP-1322](https://issues.apache.org/jira/browse/HADOOP-1322) | Tasktracker blacklist leads to hung jobs in single-node cluster |  Critical | . | Arun C Murthy | Arun C Murthy |
| [HADOOP-1312](https://issues.apache.org/jira/browse/HADOOP-1312) | heartbeat monitor thread goes away |  Blocker | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1310](https://issues.apache.org/jira/browse/HADOOP-1310) | Fix unchecked warnings in aggregate code |  Major | . | Tom White | Tom White |
| [HADOOP-1299](https://issues.apache.org/jira/browse/HADOOP-1299) | Once RPC.stopClient has been called, RPC can not be used again |  Minor | ipc | stack | stack |
| [HADOOP-1297](https://issues.apache.org/jira/browse/HADOOP-1297) | datanode sending block reports to namenode once every second |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1294](https://issues.apache.org/jira/browse/HADOOP-1294) | Fix unchecked warnings in main Hadoop code under Java 6. |  Major | test | Tom White | Tom White |
| [HADOOP-1293](https://issues.apache.org/jira/browse/HADOOP-1293) | stderr from streaming skipped after first 20 lines. |  Minor | . | Koji Noguchi | Koji Noguchi |
| [HADOOP-1279](https://issues.apache.org/jira/browse/HADOOP-1279) | list of completed jobs purges jobs based on submission not on completion age |  Major | . | Alejandro Abdelnur | Arun C Murthy |
| [HADOOP-1278](https://issues.apache.org/jira/browse/HADOOP-1278) | Fix the per-job tasktracker 'blacklist' |  Major | . | Arun C Murthy | Arun C Murthy |
| [HADOOP-1275](https://issues.apache.org/jira/browse/HADOOP-1275) | job notification property in hadoop-default.xml is misspelled |  Trivial | . | Alejandro Abdelnur |  |
| [HADOOP-1272](https://issues.apache.org/jira/browse/HADOOP-1272) | Extract InnerClasses from FSNamesystem into separate classes |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1271](https://issues.apache.org/jira/browse/HADOOP-1271) | The StreamBaseRecordReader is unable to log record data that's not UTF-8 |  Minor | . | Gautam Kowshik | Arun C Murthy |
| [HADOOP-1262](https://issues.apache.org/jira/browse/HADOOP-1262) | file corruption detected because dfs client does not use replica blocks for checksum file |  Major | . | dhruba borthakur | Hairong Kuang |
| [HADOOP-1258](https://issues.apache.org/jira/browse/HADOOP-1258) | TestCheckpoint test case doesn't wait for MiniDFSCluster to be active |  Trivial | test | Nigel Daley | Nigel Daley |
| [HADOOP-1256](https://issues.apache.org/jira/browse/HADOOP-1256) | Dfs image loading and edits loading creates multiple instances of DatanodeDescriptor for the same datanode |  Major | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1255](https://issues.apache.org/jira/browse/HADOOP-1255) | Name-node falls into infinite loop trying to remove a dead node. |  Blocker | . | Konstantin Shvachko | Hairong Kuang |
| [HADOOP-1253](https://issues.apache.org/jira/browse/HADOOP-1253) | ConcurrentModificationException and NPE in JobControl |  Minor | . | Johan Oskarsson | Johan Oskarsson |
| [HADOOP-1252](https://issues.apache.org/jira/browse/HADOOP-1252) | Disk problems should be handled better by the MR framework |  Major | . | Devaraj Das | Devaraj Das |
| [HADOOP-1244](https://issues.apache.org/jira/browse/HADOOP-1244) | stop-dfs.sh incorrectly specifies slaves file for stopping datanode |  Minor | . | Michael Bieniosek | dhruba borthakur |
| [HADOOP-1243](https://issues.apache.org/jira/browse/HADOOP-1243) | ClientProtocol.versionID should be 11 |  Major | . | Konstantin Shvachko | dhruba borthakur |
| [HADOOP-1242](https://issues.apache.org/jira/browse/HADOOP-1242) | dfs upgrade/downgrade problems |  Blocker | . | Owen O'Malley | Konstantin Shvachko |
| [HADOOP-1241](https://issues.apache.org/jira/browse/HADOOP-1241) | Null PointerException in processReport when namenode is restarted |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1239](https://issues.apache.org/jira/browse/HADOOP-1239) | Classes in src/test/testjar need package name |  Trivial | test | Jim Kellerman | Jim Kellerman |
| [HADOOP-1238](https://issues.apache.org/jira/browse/HADOOP-1238) | maps\_running metric is only updated at the end of the task |  Minor | metrics | Michael Bieniosek | David Bowen |
| [HADOOP-1224](https://issues.apache.org/jira/browse/HADOOP-1224) | "Browse the filesystem" link pointing to a dead data-node |  Major | . | Konstantin Shvachko | Enis Soztutar |
| [HADOOP-1219](https://issues.apache.org/jira/browse/HADOOP-1219) | Spurious progress messages should be discarded after a task is done |  Major | . | Devaraj Das | Devaraj Das |
| [HADOOP-1218](https://issues.apache.org/jira/browse/HADOOP-1218) | In TaskTracker the access to RunningJob object is not synchronized in one place |  Major | . | Devaraj Das | Devaraj Das |
| [HADOOP-1211](https://issues.apache.org/jira/browse/HADOOP-1211) | Remove deprecated constructor and unused static members in DataNode class |  Major | . | Konstantin Shvachko | Konstantin Shvachko |
| [HADOOP-1205](https://issues.apache.org/jira/browse/HADOOP-1205) | The open method of FSNamesystem should be synchronized |  Blocker | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1204](https://issues.apache.org/jira/browse/HADOOP-1204) | Re-factor InputFormat/RecordReader related classes |  Major | . | Runping Qi | Runping Qi |
| [HADOOP-1203](https://issues.apache.org/jira/browse/HADOOP-1203) | UpgradeUtilities should use MiniDFSCluster to start and stop NameNode/DataNodes |  Major | test | Nigel Daley | Nigel Daley |
| [HADOOP-1200](https://issues.apache.org/jira/browse/HADOOP-1200) | Datanode should periodically do a disk check |  Blocker | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1198](https://issues.apache.org/jira/browse/HADOOP-1198) | ipc.client.timeout of 2000ms for test cases seems too small; causes too many timeouts and leads to hung test cases |  Major | test | Arun C Murthy | Arun C Murthy |
| [HADOOP-1189](https://issues.apache.org/jira/browse/HADOOP-1189) | Still seeing some unexpected 'No space left on device' exceptions |  Major | . | Raghu Angadi | Raghu Angadi |
| [HADOOP-1187](https://issues.apache.org/jira/browse/HADOOP-1187) | DFS Scalability: avoid scanning entire list of datanodes in getAdditionalBlocks |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1184](https://issues.apache.org/jira/browse/HADOOP-1184) | Decommission fails if a block that needs replication has only one replica |  Major | . | dhruba borthakur |  |
| [HADOOP-1178](https://issues.apache.org/jira/browse/HADOOP-1178) | NullPointer Exception in org.apache.hadoop.dfs.NameNode.isDir on namenode restart |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1176](https://issues.apache.org/jira/browse/HADOOP-1176) | Reduce hang on huge map output |  Major | . | Hairong Kuang | Arun C Murthy |
| [HADOOP-1170](https://issues.apache.org/jira/browse/HADOOP-1170) | Very high CPU usage on data nodes because of FSDataset.checkDataDir() on every connect |  Major | . | Igor Bolotin |  |
| [HADOOP-1169](https://issues.apache.org/jira/browse/HADOOP-1169) | CopyFiles skips src files of s3 urls |  Minor | util | stack |  |
| [HADOOP-1164](https://issues.apache.org/jira/browse/HADOOP-1164) | TestReplicationPolicy doesn't use port 0 for the NameNode |  Major | test | Owen O'Malley | Owen O'Malley |
| [HADOOP-1163](https://issues.apache.org/jira/browse/HADOOP-1163) | Ganglia metrics reporting is misconfigured |  Minor | metrics | Michael Bieniosek |  |
| [HADOOP-1160](https://issues.apache.org/jira/browse/HADOOP-1160) | DistributedFileSystem doesn't close the RawDistributedFileSystem on close. |  Blocker | . | Owen O'Malley | Hairong Kuang |
| [HADOOP-1156](https://issues.apache.org/jira/browse/HADOOP-1156) | NullPointerException in MiniDFSCluster |  Major | . | Konstantin Shvachko | Hairong Kuang |
| [HADOOP-1154](https://issues.apache.org/jira/browse/HADOOP-1154) | streaming hang. (PipeMapRed$MROutputThread gone) |  Major | . | Koji Noguchi | Koji Noguchi |
| [HADOOP-1153](https://issues.apache.org/jira/browse/HADOOP-1153) | DataNode and FSNamesystem don't shutdown cleanly |  Major | . | Nigel Daley | Konstantin Shvachko |
| [HADOOP-1152](https://issues.apache.org/jira/browse/HADOOP-1152) | Reduce task hang failing in MapOutputCopier.copyOutput |  Major | . | Koji Noguchi | Tahir Hashmi |
| [HADOOP-1151](https://issues.apache.org/jira/browse/HADOOP-1151) | streaming PipeMapRed prints system info to stderr |  Trivial | . | Koji Noguchi | Koji Noguchi |
| [HADOOP-1149](https://issues.apache.org/jira/browse/HADOOP-1149) | DFS Scalability: high cpu usage in addStoredBlock |  Major | . | dhruba borthakur | Raghu Angadi |
| [HADOOP-1146](https://issues.apache.org/jira/browse/HADOOP-1146) | "Reduce input records" counter name is misleading |  Major | . | David Bowen | David Bowen |
| [HADOOP-1137](https://issues.apache.org/jira/browse/HADOOP-1137) | StatusHttpServer assumes that resources for /static are in files |  Major | . | Benjamin Reed |  |
| [HADOOP-1136](https://issues.apache.org/jira/browse/HADOOP-1136) | exception in UnderReplicatedBlocks:add when ther are more replicas of a block than required |  Major | . | dhruba borthakur | Hairong Kuang |
| [HADOOP-1122](https://issues.apache.org/jira/browse/HADOOP-1122) | Divide-by-zero exception in chooseTarget |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1114](https://issues.apache.org/jira/browse/HADOOP-1114) | bin/hadoop script clobbers CLASSPATH |  Minor | scripts | Michael Bieniosek | Doug Cutting |
| [HADOOP-1110](https://issues.apache.org/jira/browse/HADOOP-1110) | JobTracker WebUI  "Map input records" a little off. |  Trivial | . | Koji Noguchi | David Bowen |
| [HADOOP-1093](https://issues.apache.org/jira/browse/HADOOP-1093) | NNBench generates millions of NotReplicatedYetException in Namenode log |  Major | . | Nigel Daley | dhruba borthakur |
| [HADOOP-1090](https://issues.apache.org/jira/browse/HADOOP-1090) | In SortValidator, the check for whether a file belongs to sort-input or sort-output dir is weak |  Major | . | Devaraj Das | Arun C Murthy |
| [HADOOP-1085](https://issues.apache.org/jira/browse/HADOOP-1085) | Remove 'port rolling' from Mini{DFS\|MR}Cluster |  Major | test | Arun C Murthy | Arun C Murthy |
| [HADOOP-1081](https://issues.apache.org/jira/browse/HADOOP-1081) | JAVA\_PLATFORM with spaces (i.e. Mac OS X-ppc-32) breaks bin/hadoop script |  Major | scripts | Andrzej Bialecki |  |
| [HADOOP-1073](https://issues.apache.org/jira/browse/HADOOP-1073) | DFS Scalability: high CPU usage in choosing replication targets and file open |  Major | . | dhruba borthakur | Hairong Kuang |
| [HADOOP-1071](https://issues.apache.org/jira/browse/HADOOP-1071) | RPC$VersionMismatch exception is not fatal to JobTracker |  Major | . | Nigel Daley | Tahir Hashmi |
| [HADOOP-1064](https://issues.apache.org/jira/browse/HADOOP-1064) | dfsclient logging messages should have appropriate log levels |  Major | . | dhruba borthakur | dhruba borthakur |
| [HADOOP-1063](https://issues.apache.org/jira/browse/HADOOP-1063) | MiniDFSCluster exists a race condition that lead to data node resources are not properly released |  Major | test | Hairong Kuang | Hairong Kuang |
| [HADOOP-1061](https://issues.apache.org/jira/browse/HADOOP-1061) | S3 listSubPaths bug |  Critical | fs | Mike Smith |  |
| [HADOOP-1050](https://issues.apache.org/jira/browse/HADOOP-1050) | Do not count lost tasktracker against the job |  Major | . | Arun C Murthy | Arun C Murthy |
| [HADOOP-1047](https://issues.apache.org/jira/browse/HADOOP-1047) | TestReplication fails because DFS does not guarantee all the replicas are placed when a file is closed |  Major | . | Hairong Kuang | Hairong Kuang |
| [HADOOP-1011](https://issues.apache.org/jira/browse/HADOOP-1011) | ConcurrentModificationException in JobHistory |  Major | . | Nigel Daley | Tahir Hashmi |
| [HADOOP-1001](https://issues.apache.org/jira/browse/HADOOP-1001) | the output of the map is not type checked against the specified types |  Major | . | Owen O'Malley | Tahir Hashmi |
| [HADOOP-672](https://issues.apache.org/jira/browse/HADOOP-672) | dfs shell enhancements |  Minor | . | Yoram Arnon | dhruba borthakur |


### TESTS:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |


### SUB-TASKS:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |


### OTHER:

| JIRA | Summary | Priority | Component | Reporter | Contributor |
|:---- |:---- | :--- |:---- |:---- |:---- |


