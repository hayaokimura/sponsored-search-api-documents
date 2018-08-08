# TargetingList
TargetingList is an object that holds retargeting information (target list).

### Service
+ [RetargetingListService](../services/RetargetingListService.md)

<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
  <th>response</th>
  <th>add</th>
  <th>set</th>
  <th>remove</th>
 </tr>
 <tr>
  <td>accountId</td>
  <td>xsd:long</td>
  <td>Account ID.</td>
  <td>yes</td>
  <td>Requirement</td>
  <td>Requirement</td>
  <td>-</td>
 </tr>
 <tr>
  <td>owner</td>
  <td><a href="./TargetListOwner.md">TargetListOwner</a></td>
  <td>Target list owner information.</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>retargetingAccountStatus</td>
  <td><a href="./RetargetingAccountStatus.md">RetargetingAccountStatus</a></td>
  <td>Status of Retargeting account.</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>targetListId</td>
  <td>xsd:long</a></td>
  <td>Target List ID.</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement</td>
  <td>-</td>
 </tr>
 <tr>
  <td>targetListTrackId</td>
  <td>xsd:long</a></td>
  <td>Tracking ID of Target list.</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>targetListType</td>
  <td>enum <a href="./TargetListType.md">TargetListType</a></td>
  <td>Type of Target List.</td>
  <td>yes</td>
  <td>Requirement</td>
  <td>Requirement</td>
  <td>-</td>
 </tr>
 <tr>
  <td>targetListName</td>
  <td>xsd:string</a></td>
  <td>Target List name.</td>
  <td>yes</td>
  <td>Requirement</td>
  <td>Optional</td>
  <td>-</td>
 </tr>
 <tr>
  <td>targetListDescription</td>
  <td>xsd:string</a></td>
  <td>Description of Target List.</td>
  <td>yes</td>
  <td>Optional</td>
  <td>Optional</td>
  <td>-</td>
 </tr>
 <tr>
  <td>reachStorageStatus</td>
  <td>enum <a href="./ReachStorageStatus.md">ReachStorageStatus</a></td>
  <td>Flag status of holding Cookie.<br>*Default: OPEN<br>*Always be "OPEN" for default list.</td>
  <td>yes</td>
  <td>Optional<br>*Ignore for LogicalTargetList</td>
  <td>Optional<br>*Ignore for LogicalTargetList</td>
  <td>-</td>
 </tr>
 <tr>
  <td>reachStorageSpan</td>
  <td>xsd:long</a></td>
  <td>Days to hold Cookie.<br>*Default: 180<br>*Can set from 1-540 days</td>
  <td>yes</td>
  <td>-</td>
  <td>Optional<br>*Ignore for LogicalTargetList</td>
  <td>-</td>
 </tr>
 <tr>
  <td>reach</td>
  <td>xsd:long</a></td>
  <td>Number of users stored to the list.</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
</table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>


