# Contributing

`.arcconfig` and `.arclint` is for my own use; you do not need it. GitHub PR is just fine.

## Criteria

### Domains

Domains directly owned by the 'target entity', and third party domains de facto controlled by 'target entity' will be listed.

For the purpose of this list, 'de facto control' is defined as 'substantial editorial/infrastructure control' over the contents of the domain. For example, KakaoStyle (`zigzag.kr`) has substantial editorial control over `zigzagkr.zendesk.com`, so it is listed there.

### Entity ownership

- Korean entity: Determined by [FSS DART](https://dart.fss.or.kr) publication; see notes in Korean below.
- Non-Korean entity: Use your best judgement; but you need proof for it.

#### 한국산 도메인 한정

- 대규모기업집단공시 대상 기업의 경우 다음의 조건에 따라 등재합니다.
  - `대규모기업집단공시 (연1회공시및 1/4분기용(대표회사))` (이하 `연1회공시`) 공시의 대표회사의 대외명칭을 파일명으로 정하고, 대표회사의 서비스와 그 종속회사의 서비스에 사용되는 도메인을 해당 리스트 내에 등재한다.
  - 예를 들어, "라인"은 2024년 5월 네이버(주) 대표회사의 `연1회공시`에서 국내/국외 계열회사로 분류되어 있으므로 `data/naver.json` 에 등재한다.
  - 언론 보도와 해당 기업 공시를 (`연1회공시` 제외) 통해 소유관계의 변동이 확인되는 경우 그 변동사항을 반영할 수 있다.
- 대규모기업집단공시 미대상 기업의 경우 다음의 조건에 따라 등재합니다.
  - 대표 서비스를 운영하는 기업을 대표기업으로 정의하고, 대표 서비스의 영문명을 파일명으로 정한다.
  - 대표기업의 자회사 (`한국채택국제회계기준 (K-IFRS) 제1110호 연결재무제표`[^1] 문단 7에서 규정한 "지배력"을 행사하는 기업) 가 운영하는 서비스의 도메인을 등재한다.
  - 그 외 관계기업 및 공동약정의 경우 알려진 정보를 기준으로 판단한다.

[^1]: [한국채택국제회계기준 (K-IFRS) 제1110호 연결재무제표](https://www.kasb.or.kr/fe/accstd/NR_view.do?sortCd=K-IFRS&divCd=01&ctgCd=&currentPage=1&rowPerPage=999999&subSearchVal=&searchVal=&accstdSeq=79&searchDateKey=1000&searchStartDt=&searchEndDt=&searchKey=1000&searchValue=)
