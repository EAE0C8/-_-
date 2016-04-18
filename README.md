<h3 class="h3--module">기본 클레스 네이밍</h3>
공통적인 클레스 네이밍을 기준으로 파생해 클레스 네이밍을 정의한다
	
	<table class="ui-data-table min">
		<caption>기본 클레스</caption>
		<colgroup>
			<col style="width:20%">
			<col style="width:30%">
			<col style="width:50%">
		</colgroup>
		<thead>
		<tr>
			<th>분류</th>
			<th>네이밍</th>
			<th>부가설명</th>
		</tr>
		</thead>
		<tbody>
		<tr>
			<th rowspan="3">영역 [ ID ]</th>
			<td>#dHead</td>
			<td>상단 감싸는 영역</td>
		</tr>
		<tr>
			<td>#dBody</td>
			<td>본문 감싸는 영역 [skip-nav 사용 영역]</td>
		</tr>
		<tr>
			<td>#dFoot / #footArea</td>
			<td>하단 영역 [개편 시 수정 안됨 - 향 후 개선]</td>
		</tr>
		<tr>
			<th>영역 [ ID ]</th>
			<td>#container</td>
			<td>페이지를 감싸는 전체영역 [자주 사용하지 않음]</td>
		</tr>
		<tr>
			<th rowspan="10">영역 [ CLASS ]</th>
			<td>.column</td>
			<td>메인에서만 사용을 지향</td>
		</tr>
		<tr>
			<td>.section</td>
			<td>제목 태그를 가지고 있으면서 영역을 구분 시 사용<em>html5 section 태그 사용으로 향후 클레스 네이밍 변경 예정</em></td>
		</tr>
		<tr>
			<td>.module</td>
			<td>section 안에 사용되거나 모듈별 구분 시 사용</td>
		</tr>
		<tr>
			<td>.cover</td>
			<td>단순하게 css 적으로 플롯팅 해제 등 단순하게 감싸거나 디자인적인 면에서 필요 시 사용</td>
		</tr>
		<tr>
			<td>.area -&gt; .block -&gt; .spot</td>
			<td>module 안에 사용되거나 버튼이나 작은 영역을 감쌀때  사용</td>
		</tr>
		<tr>
			<td>.add</td>
			<td>단순하게 디자인이 변경될 경우 기본 클레스에 추가될 경우 사용 단독으로 [ 사용불가능!! ] </td>
		</tr>
		<tr>
			<td>.style</td>
			<td>기본클레스에서 디자인이 변경될 경우 사용 [디자인 추가 시 style 로 기본 작성한다]</td>
		</tr>
		<tr>
			<td>.type</td>
			<td>기본 구조에서 디자인 외 구조가 변경될 경우 사용</td>
		</tr>
		<tr>
			<td>.cell</td>
			<td>이미지 스프라이트 기법 이나 각각 적용시 적용 </td>
		</tr>
		<tr>
			<td>.range</td>
			<td>left(.range1) right(.range2) center(.range3) 정렬 시 사용</td>
		</tr>
		<tr>
			<th>서브 영역 [ sub ]</th>
			<td>.sub-xxx </td>
			<td>메인 클레스와 같이 정의함 [단독으로 사용 불가능] ex).module.sub-xxx {... </td>
		</tr></tbody>
	</table>
