# AdGroupCriterion
AdGroupCriterionオブジェクトは、広告グループのクライテリアを表します。

### Service
+ [AdGroupCriterionService](../../services/AdGroupCriterionService.md)

### Namespace
[AdGroupCriterionService#Namespace](../../services/AdGroupCriterionService.md#namespace)

<table>
 <tr>
  <th>Field</th>
  <th>Type</th>
  <th>Description</th>
  <th>response</th>
  <th>get</th>
  <th>add</th>
  <th>set</th>
  <th>remove</th>
 </tr>
 <tr>
  <td>accountId</td>
  <td>xsd:long</td>
  <td>アカウントIDです。</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>campaignId</td>
  <td>xsd:long</td>
  <td>キャンペーンIDです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement<br><i>NotUpdatable</i></td>
  <td>Requirement<br><i>NotUpdatable</i></td>
  <td>Requirement<br><i>NotUpdatable</i></td>
 </tr>
 <tr>
  <td>campaignTrackId</td>
  <td>xsd:long</td>
  <td>トラッキング用キャンペーンIDです。</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>campaignName</td>
  <td>xsd:string</td>
  <td>キャンペーン名です。</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>adGroupId</td>
  <td>xsd:long</td>
  <td>広告グループIDです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement<br><i>NotUpdatable</i></td>
  <td>Requirement<br><i>NotUpdatable</i></td>
  <td>Requirement<br><i>NotUpdatable</i></td>
 </tr>
 <tr>
  <td>adGroupTrackId</td>
  <td>xsd:long</td>
  <td>トラッキング用広告グループIDです。</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>adGroupName</td>
  <td>xsd:string</td>
  <td>広告グループ名です。</td>
  <td>yes</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
  <td>-</td>
 </tr>
 <tr>
  <td>criterionUse</td>
  <td>enum <a href="AdGroupCriterionUse.md">AdGroupCriterionUse</a></td>
  <td>キーワードの種類です。入札キーワードか、検索対象外キーワードかを選択します。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement</td>
  <td>Requirement</td>
  <td>Requirement</td>
 </tr>
 <tr>
  <td>criterion</td>
  <td><a href="Criterion.md">Criterion</a><br>inherited <a href="Keyword.md">Keyword</a></td>
  <td>広告グループのクライテリアです。</td>
  <td>yes</td>
  <td>-</td>
  <td>Requirement</td>
  <td>Requirement<br><i>NotUpdatable</i></td>
  <td>Requirement<br><i>NotUpdatable</i></td>
 </tr>
</table>

<a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/2.1/jp/88x31.png" /></a><br />この 作品 は <a rel="license" href="http://creativecommons.org/licenses/by-nd/2.1/jp/">クリエイティブ・コモンズ 表示 - 改変禁止 2.1 日本 ライセンスの下に提供されています。</a>
