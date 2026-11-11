# 124–133장 약학정보원 약제 링크 적용 내역

확인일: 2026-11-11(한국 시간). 124장부터 133장까지 순서대로 작업했습니다.

기존 링크를 검증하고 누락된 상품명·함량 링크를 보완했습니다. 본문은 같은 품목당 한 번만 연결했고, 처방례에는 코드블록 아래에 별도로 연결했습니다. 상품명 없는 성분 처방·조제약에는 임의의 상품을 대입하지 않았습니다. 함량 링크를 추가할 때에는 기존 용량 문자열에 링크만 씌워 문구를 유지했습니다.

임상 본문·처방 용량·핵심 복약 지도·환자 안내서·Mermaid는 유지했습니다. 원본과 수정본에서 약제 링크·처방례 약제 정보 줄·132장의 추가 제품 링크 줄을 제외한 문자가 동일한지 대조했고, 처방 코드블록·핵심 복약 지도·환자 안내서·Mermaid는 별도로 원문 일치를 확인했습니다. 이 작업은 약제 링크 적용이며 전체 임상 내용을 새로 검토한 결과를 뜻하지 않습니다.

132장은 사용자가 제공한 야일라 10·20 ㎎ 정제와 엠빅스에스 50·100 ㎎ 구강붕해필름을 기존 약제표 바로 아래 ‘제품별 상세 정보’ 줄에 추가했습니다. 기존 레비트라·엠빅스 상품명과 임상 용량은 유지했습니다. 총 본문 링크 **161곳**, 처방례 **50개** 중 약제가 있는 **49개**의 약제 정보 링크 **58곳**을 확인했습니다. 처방례 주석의 에스트레바겔 링크 1곳은 별도로 유지했습니다. 전체 연결 품목은 중복을 제외하면 103개입니다. 적용한 상세 페이지는 HTTP 200 응답과 제품 정보를 확인했습니다. 페이지 열림과 품목정보 확인은 실제 공급 여부의 확인과는 구분됩니다.

## 적용 요약

| 장 | 파일명 | 본문 링크 | 처방례 | 약제 정보 링크 |
|---|---|---:|---:|---:|
| 124 | 124_-bph.md | 28 | 4 | 6 |
| 125 | 125_-urinary-incontinence.md | 20 | 5 | 5 |
| 126 | 126_-overactive-bladder-oab.md | 16 | 5 | 7 |
| 127 | 127_-premenstrual-syndrome-pms.md | 21 | 3 | 3 |
| 128 | 128_-dysmenorrhea.md | 8 | 3 | 4 |
| 129 | 129_-abnormal-uterine-bleeding.md | 9 | 5 | 6 |
| 130 | 130_-amenorrhea.md | 6 | 4 | 4 |
| 131 | 131_-contraception.md | 16 | 6 | 6 |
| 132 | 132_-sexual-dysfunction.md | 23 | 8 | 9 |
| 133 | 133_-urolithiasis.md | 14 | 7 | 8 |

## 미적용·추가 확인 사항

| 장 | 항목 | 처리 |
|---|---|---|
| 127 | 프리페민 추출물 표현 | 본문의 ‘건조 추출물’과 약학정보원 성분명의 ‘연조엑스’ 표기가 다릅니다. 추출물·최종 제제의 표현 차이인지 추가 대조가 필요하며, 확정 오류로 단정하거나 임상 문구를 바꾸지 않았습니다. [품목 정보](https://www.health.kr/drug/2013061000010) |
| 131 | 노바-티 | 의료기기이므로 의약품 상세 페이지를 임의 연결하지 않았습니다. |
| 131 | Lunelle/Cyclofem·Xulane·Twirla·Annovera | 해외 제품 예시의 정확한 약학정보원 품목을 확인하지 못해 미적용했습니다. |
| 131 | 프리모루트엔 | 원고에서 공급 미확인으로 설명된 과거 제품이며 확인하지 못한 상세 링크를 만들지 않았습니다. |
| 132 | 레비트라 5·10·20 ㎎ | 검색상의 품목 기록과 달리 상세 페이지는 HTTP 404였습니다. 해당 상품명에는 연결하지 않고, 사용자가 제공한 야일라 10·20 ㎎을 실제 상품명으로 별도 연결했습니다. |
| 132 | 엠빅스 100 ㎎ | 검색상의 품목 기록은 있으나 상세 페이지는 HTTP 404였습니다. 50 ㎎ 정제 링크를 유지하고 사용자가 제공한 엠빅스에스 필름 50·100 ㎎을 별도로 연결했습니다. |
| 132 | 비아그라 25 ㎎ | 품목 정보에 취소일 2026-04-01이 표시되어 현행 제품 링크로 추가하지 않았습니다. sildenafil 25 ㎎ 용량은 유지했고, 처방례의 팔팔츄정 25 ㎎은 해당 제품에 연결했습니다. [취소 품목 정보](https://www.health.kr/drug/A11ABBBBB0960) |

아래 표는 유지·이동·신규 적용을 포함한 최종 연결 목록입니다. 각 링크의 표시 문구와 실제 제품명을 함께 기재했습니다. 링크가 용량 숫자에 붙어 있는 경우에도 해당 행의 상품에 속하는 함량입니다.

## 124장 — 124_-bph.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [카두라 엑스엘](https://www.health.kr/drug/A11AGGGGA5795) | 카두라엑스엘서방정4mg | 독사조신메실산염 ( Doxazosin Mesylate ) 5.09 mg ( 독사조신으로서 4.2mg ) | 서방정 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [하이트린](https://www.health.kr/drug/A11A0950A0397) | 일양하이트린정1mg | 테라조신염산염수화물 ( Terazosin Hydrochloride Hydrate ) 1.18 mg | 정제 | 일양약품 | 검증·유지/첫 등장 정리 |
| [자트랄 엑스엘](https://www.health.kr/drug/A11AJJJJJ0228) | 자트랄엑스엘정10mg | 알푸조신염산염 ( Alfuzosin Hydrochloride ) 10 mg | 서방정 | 한독 | 검증·유지/첫 등장 정리 |
| [하루날 디](https://www.health.kr/drug/A11AOOOOO9776) | 하루날디정0.2mg | 탐스로신염산염 ( Tamsulosin Hydrochloride ) 0.2 mg | 속붕해정(구강붕해정) | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [트루패스](https://health.kr/drug/2015050100116) | 트루패스구강붕해정8mg | 실로도신 ( Silodosin ) 8 mg | 속붕해정(구강붕해정) | 제이더블유중외제약 | 검증·유지/첫 등장 정리 |
| [4 ㎎](https://www.health.kr/drug/2014042500006) | 트루패스정4mg | 실로도신 ( Silodosin ) 4 mg | 정제 | 제이더블유중외제약 | 추가·함량 보완 |
| [플리바스](https://health.kr/drug/2011050200001) | 플리바스정25mg | 나프토피딜 ( Naftopidil ) 25 mg | 정제 | 동아에스티 | 검증·유지/첫 등장 정리 |
| [50](https://www.health.kr/drug/2011050200003) | 플리바스정50mg | 나프토피딜 ( Naftopidil ) 50 mg | 정제 | 동아에스티 | 추가·함량 보완 |
| [75 ㎎](https://www.health.kr/drug/2011050200002) | 플리바스정75mg | 나프토피딜 ( Naftopidil ) 75 mg | 정제 | 동아에스티 | 추가·함량 보완 |
| [디트로판](https://www.health.kr/drug/A11A0570A0291) | 동화디트로판정 | 옥시부티닌염산염 ( Oxybutynin Hydrochloride ) 5 mg | 정제 | 동화약품 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11AFFFFF0216) | 비유피4정10mg | 프로피베린염산염 ( Propiverine Hydrochloride ) 10 mg | 정제 | 제일약품 | 추가·함량 보완 |
| [비유피-4](https://www.health.kr/drug/A11ABBBBB1253) | 비유피4정20mg | 프로피베린염산염 ( Propiverine Hydrochloride ) 20 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |
| [2 ㎎](https://www.health.kr/drug/A11AOOOOO8685) | 디트루시톨SR캡슐2mg | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 2 mg | 서방캡슐 | 비아트리스코리아 | 추가·함량 보완 |
| [디트루시톨 SR](https://www.health.kr/drug/A11AOOOOO3053) | 디트루시톨SR캡슐4mg | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 4 mg | 서방캡슐 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11APPPPP1279) | 베시케어정10mg | 솔리페나신숙신산염 ( Solifenacin Succinate ) 10 mg | 정제 | 한국아스텔라스제약 | 추가·함량 보완 |
| [베시케어](https://www.health.kr/drug/A11APPPPP1278) | 베시케어정5mg | 솔리페나신숙신산염 ( Solifenacin Succinate ) 5 mg | 정제 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [8 ㎎](https://www.health.kr/drug/A11AKP08L0251) | 토비애즈서방정8mg | 페소테로딘푸마르산염 ( Fesoterodine Fumarate ) 8 mg | 서방정 | 한국화이자제약 | 추가·함량 보완 |
| [토비애즈](https://www.health.kr/drug/A11AKP08L0252) | 토비애즈서방정4mg | 페소테로딘푸마르산염 ( Fesoterodine Fumarate ) 4 mg | 서방정 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [유리토스](https://www.health.kr/drug/2009071505302) | 유리토스정 | 이미다페나신 ( Imidafenacin ) 0.1 mg | 정제 | 엘지화학 | 검증·유지/첫 등장 정리 |
| [스파스몰리트](https://www.health.kr/drug/A11A1310A0221) | 스파스몰리트당의정 | 트로스퓸염화물 ( Trospium Chloride ) 20 mg | 정제 | 부광약품 | 검증·유지/첫 등장 정리 |
| [프로스카](https://www.health.kr/drug/A11ABBBBB0944) | 프로스카정 | 피나스테리드 ( Finasteride ) 5 mg | 정제 | 한국오가논 | 검증·유지/첫 등장 정리 |
| [아보다트](https://www.health.kr/drug/A11AOOOOO4032) | 아보다트연질캡슐0.5mg | 두타스테리드 ( Dutasteride ) 0.5 mg | 연질캡슐 | 글락소스미스클라인 | 검증·유지/첫 등장 정리 |
| [베타미가](https://www.health.kr/drug/2014010200015) | 베타미가서방정50mg | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [25 ㎎](https://www.health.kr/drug/2014010200016) | 베타미가서방정25mg | 미라베그론 ( Mirabegron ) 25 mg | 서방정 | 한국아스텔라스제약 | 추가·함량 보완 |
| [베오바](https://www.health.kr/drug/2022110100005) | 베오바정50mg | 비베그론 ( Vibegron ) 50 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |
| [유레스코 등](https://www.health.kr/drug/2025012400002) | 유레스코정0.5/5mg | 두타스테리드 ( Dutasteride ) 0.5 mg 타다라필 ( Tadalafil ) 5 mg | 정제 | 동국제약 | 검증·유지/첫 등장 정리 |
| [시알리스](https://www.health.kr/drug/A11AKP08G3782) | 시알리스정5mg | 타다라필 ( Tadalafil ) 5 mg | 정제 | 지피테라퓨틱스코리아 | 검증·유지/첫 등장 정리 |
| [녹더나](https://www.health.kr/drug/2017102500005) | 녹더나설하정50μg | 데스모프레신아세트산염 ( Desmopressin Acetate ) 0.057 mg ( 데스모프레신으로서 0.05mg ) | 설하정 | 한국페링제약 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [자트랄엑스엘정·10 ㎎](https://www.health.kr/drug/A11AJJJJJ0228) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [프로스카정·5 ㎎](https://www.health.kr/drug/A11ABBBBB0944) · [트루패스구강붕해정·8 ㎎](https://health.kr/drug/2015050100116) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [플리바스정·25 ㎎](https://health.kr/drug/2011050200001) · [베시케어정·5 ㎎](https://www.health.kr/drug/A11APPPPP1278) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [시알리스정·5 ㎎](https://www.health.kr/drug/A11AKP08G3782) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 카두라 엑스엘 8 ㎎은 4 ㎎ 서방정의 투여용량으로 구분하고 8 ㎎ 품목을 임의 생성하지 않음.
- 유리토스 0.2 ㎎ 투여량에는 확인된 0.1 ㎎ 정제 정보만 연결.
- 하이트린 1~10 ㎎/일은 투여량 범위이며 확인된 초회 1 ㎎ 품목을 연결.

## 125장 — 125_-urinary-incontinence.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [토비애즈](https://www.health.kr/drug/A11AKP08L0252) | 토비애즈서방정4mg | 페소테로딘푸마르산염 ( Fesoterodine Fumarate ) 4 mg | 서방정 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [8 ㎎](https://www.health.kr/drug/A11AKP08L0251) | 토비애즈서방정8mg | 페소테로딘푸마르산염 ( Fesoterodine Fumarate ) 8 mg | 서방정 | 한국화이자제약 | 추가·함량 보완 |
| [유리토스](https://www.health.kr/drug/2009071505302) | 유리토스정 | 이미다페나신 ( Imidafenacin ) 0.1 mg | 정제 | 엘지화학 | 검증·유지/첫 등장 정리 |
| [동화디트로판](https://www.health.kr/drug/A11A0570A0291) | 동화디트로판정 | 옥시부티닌염산염 ( Oxybutynin Hydrochloride ) 5 mg | 정제 | 동화약품 | 검증·유지/첫 등장 정리 |
| [비유피-4](https://www.health.kr/drug/A11ABBBBB1253) | 비유피4정20mg | 프로피베린염산염 ( Propiverine Hydrochloride ) 20 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |
| [베시케어](https://www.health.kr/drug/A11APPPPP1278) | 베시케어정5mg | 솔리페나신숙신산염 ( Solifenacin Succinate ) 5 mg | 정제 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11APPPPP1279) | 베시케어정10mg | 솔리페나신숙신산염 ( Solifenacin Succinate ) 10 mg | 정제 | 한국아스텔라스제약 | 추가·함량 보완 |
| [디트루시톨 SR](https://www.health.kr/drug/A11AOOOOO3053) | 디트루시톨SR캡슐4mg | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 4 mg | 서방캡슐 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [2 ㎎](https://www.health.kr/drug/A11AOOOOO8685) | 디트루시톨SR캡슐2mg | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 2 mg | 서방캡슐 | 비아트리스코리아 | 추가·함량 보완 |
| [스파스몰리트](https://www.health.kr/drug/A11A1310A0221) | 스파스몰리트당의정 | 트로스퓸염화물 ( Trospium Chloride ) 20 mg | 정제 | 부광약품 | 검증·유지/첫 등장 정리 |
| [25 ㎎](https://www.health.kr/drug/2014010200016) | 베타미가서방정25mg | 미라베그론 ( Mirabegron ) 25 mg | 서방정 | 한국아스텔라스제약 | 추가·함량 보완 |
| [베타미가](https://www.health.kr/drug/2014010200015) | 베타미가서방정50mg | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [베오바](https://www.health.kr/drug/2022110100005) | 베오바정50mg | 비베그론 ( Vibegron ) 50 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |
| [자트랄 엑스엘](https://www.health.kr/drug/A11AJJJJJ0228) | 자트랄엑스엘정10mg | 알푸조신염산염 ( Alfuzosin Hydrochloride ) 10 mg | 서방정 | 한독 | 검증·유지/첫 등장 정리 |
| [하루날 디](https://www.health.kr/drug/A11AOOOOO9776) | 하루날디정0.2mg | 탐스로신염산염 ( Tamsulosin Hydrochloride ) 0.2 mg | 속붕해정(구강붕해정) | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [4 ㎎](https://www.health.kr/drug/2014042500006) | 트루패스정4mg | 실로도신 ( Silodosin ) 4 mg | 정제 | 제이더블유중외제약 | 추가·함량 보완 |
| [트루패스](https://health.kr/drug/2015050100116) | 트루패스구강붕해정8mg | 실로도신 ( Silodosin ) 8 mg | 속붕해정(구강붕해정) | 제이더블유중외제약 | 검증·유지/첫 등장 정리 |
| [프로스카](https://www.health.kr/drug/A11ABBBBB0944) | 프로스카정 | 피나스테리드 ( Finasteride ) 5 mg | 정제 | 한국오가논 | 검증·유지/첫 등장 정리 |
| [아보다트](https://health.kr/drug/A11AOOOOO4032) | 아보다트연질캡슐0.5mg | 두타스테리드 ( Dutasteride ) 0.5 mg | 연질캡슐 | 글락소스미스클라인 | 검증·유지/첫 등장 정리 |
| [보톡스주](https://www.health.kr/drug/A11AKP08G2664) | 보톡스주 | 클로스트리디움보툴리눔독소A형 ( Clostridium Botulinum Toxin Type A ) 100 U | 주사제 | 한국애브비 | 추가·함량 보완 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [베시케어정·5 ㎎](https://www.health.kr/drug/A11APPPPP1278) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [베타미가서방정·50 ㎎](https://www.health.kr/drug/2014010200015) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | 약제 없음(운동·페서리 예시) — 정보 줄 미추가 | 비약물 처방례 |
| 4 | [하루날디정·0.2 ㎎](https://www.health.kr/drug/A11AOOOOO9776) · [아보다트연질캡슐·0.5 ㎎](https://health.kr/drug/A11AOOOOO4032) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [디트루시톨SR캡슐·4 ㎎](https://www.health.kr/drug/A11AOOOOO3053) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 유리토스 0.2 ㎎ 투여량은 0.1 ㎎ 제품 정보와 구분.
- 하루날 디 0.4 ㎎ 증량은 0.2 ㎎ 정제 기준이며 별도 0.4 ㎎ 상품을 임의로 연결하지 않음.
- 트루패스 2 ㎎ 감량은 4 ㎎ 정제와 구분하며 2 ㎎ 캡슐/구강붕해정을 임의 선택하지 않음.
- 처방례 3은 운동·페서리로 약제가 없어 약제 정보 줄을 추가하지 않음.

## 126장 — 126_-overactive-bladder-oab.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [보톡스](https://www.health.kr/drug/A11AKP08G2664) | 보톡스주 | 클로스트리디움보툴리눔독소A형 ( Clostridium Botulinum Toxin Type A ) 100 U | 주사제 | 한국애브비 | 추가·함량 보완 |
| [미니린정](https://www.health.kr/drug/A11ABBBBB2539) | 미니린정0.1mg | 데스모프레신아세트산염 ( Desmopressin Acetate ) 100 μg | 정제 | 한국페링제약 | 추가·함량 보완 |
| [녹더나설하정](https://www.health.kr/drug/2017102500004) | 녹더나설하정25μg | 데스모프레신아세트산염 ( Desmopressin Acetate ) 0.028 mg ( 데스모프레신으로서 0.025mg ) | 설하정 | 한국페링제약 | 추가·함량 보완 |
| [50 μg](https://www.health.kr/drug/2017102500005) | 녹더나설하정50μg | 데스모프레신아세트산염 ( Desmopressin Acetate ) 0.057 mg ( 데스모프레신으로서 0.05mg ) | 설하정 | 한국페링제약 | 추가·함량 보완 |
| [디트루시톨SR](https://www.health.kr/drug/A11AOOOOO3053) | 디트루시톨SR캡슐4mg | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 4 mg | 서방캡슐 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [스파스몰리트](https://www.health.kr/drug/A11A1310A0221) | 스파스몰리트당의정 | 트로스퓸염화물 ( Trospium Chloride ) 20 mg | 정제 | 부광약품 | 검증·유지/첫 등장 정리 |
| [베시케어](https://www.health.kr/drug/A11APPPPP1278) | 베시케어정5mg | 솔리페나신숙신산염 ( Solifenacin Succinate ) 5 mg | 정제 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [토비애즈](https://www.health.kr/drug/A11AKP08L0252) | 토비애즈서방정4mg | 페소테로딘푸마르산염 ( Fesoterodine Fumarate ) 4 mg | 서방정 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [유리토스](https://www.health.kr/drug/2009071505302) | 유리토스정 | 이미다페나신 ( Imidafenacin ) 0.1 mg | 정제 | 엘지화학 | 검증·유지/첫 등장 정리 |
| [동화디트로판](https://www.health.kr/drug/A11A0570A0291) | 동화디트로판정 | 옥시부티닌염산염 ( Oxybutynin Hydrochloride ) 5 mg | 정제 | 동화약품 | 검증·유지/첫 등장 정리 |
| [비유피-4](https://www.health.kr/drug/A11ABBBBB1253) | 비유피4정20mg | 프로피베린염산염 ( Propiverine Hydrochloride ) 20 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |
| [베타미가](https://www.health.kr/drug/2014010200015) | 베타미가서방정50mg | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 한국아스텔라스제약 | 검증·유지/첫 등장 정리 |
| [25 ㎎](https://www.health.kr/drug/2014010200016) | 베타미가서방정25mg | 미라베그론 ( Mirabegron ) 25 mg | 서방정 | 한국아스텔라스제약 | 추가·함량 보완 |
| [미라벡](https://www.health.kr/drug/2020040100032) | 미라벡서방정50mg | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 한미약품 | 검증·유지/첫 등장 정리 |
| [셀레베타](https://www.health.kr/drug/2020040100031) | 셀레베타서방정50mg | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 종근당 | 검증·유지/첫 등장 정리 |
| [베오바](https://www.health.kr/drug/2022110100005) | 베오바정50mg | 비베그론 ( Vibegron ) 50 mg | 정제 | 제일약품 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [디트루시톨SR캡슐·4 ㎎](https://www.health.kr/drug/A11AOOOOO3053) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [베타미가서방정·50 ㎎](https://www.health.kr/drug/2014010200015) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [베오바정·50 ㎎](https://www.health.kr/drug/2022110100005) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [베시케어정·5 ㎎](https://www.health.kr/drug/A11APPPPP1278) · [베타미가서방정·50 ㎎](https://www.health.kr/drug/2014010200015) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [하루날디정·0.2 ㎎](https://www.health.kr/drug/A11AOOOOO9776) · [베타미가서방정·50 ㎎](https://www.health.kr/drug/2014010200015) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 보톡스 100 U/바이알, 미니린정 0.1 ㎎, 녹더나 25·50 ㎍의 본문 첫 언급을 연결.
- 미라벡·셀레베타는 명시된 대표 50 ㎎ 제품을 유지.
- 용량이 없는 항무스카린제는 기존 대표 용량 링크를 검증하여 유지.

## 127장 — 127_-premenstrual-syndrome-pms.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [푸록틴 20 ㎎](https://www.health.kr/drug/A11APPPPP0558) | 푸록틴확산정20mg | 플루옥세틴염산염 ( Fluoxetine Hydrochloride ) 22.37 mg ( 플루옥세틴으로서 20mg ) | 현탁정 | 명인제약 | 검증·유지/첫 등장 정리 |
| [20 ㎎](https://www.health.kr/drug/2009090700007) | 렉사프로정20mg | 에스시탈로프람옥살산염 ( Escitalopram Oxalate ) 25.54 mg ( 에스시탈로프람으로서 20mg ) | 정제 | 한국룬드벡 | 추가·함량 보완 |
| [렉사프로](https://www.health.kr/drug/A11AOOOOO5474) | 렉사프로정10mg | 에스시탈로프람옥살산염 ( Escitalopram Oxalate ) 12.77 mg ( 에스시탈로프람으로서 10mg ) | 정제 | 한국룬드벡 | 검증·유지/첫 등장 정리 |
| [100 ㎎](https://www.health.kr/drug/2010122700001) | 졸로푸트정100mg | 설트랄린염산염 ( Sertraline Hydrochloride ) 111.9 mg ( 설트랄린으로서 100mg ) | 정제 | 비아트리스코리아 | 추가·함량 보완 |
| [졸로푸트](https://www.health.kr/drug/A11A0310A0239) | 졸로푸트정50mg | 설트랄린염산염 ( Sertraline Hydrochloride ) 55.95 mg ( 설트랄린으로서 50mg ) | 정제 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [세로자트](https://www.health.kr/drug/A11A0740A0377) | 한독세로자트정20mg | 파록세틴염산염수화물 ( Paroxetine Hydrochloride Hydrate ) 22.88 mg ( 파록세틴으로서 20mg ) | 정제 | 한독 | 검증·유지/첫 등장 정리 |
| [25 ㎎](https://www.health.kr/drug/2021062400006) | 파로자트씨알정25mg | 파록세틴염산염수화물 ( Paroxetine Hydrochloride Hydrate ) 28.5 mg ( 파록세틴으로서 25mg ) | 장용성서방정 | 한림제약 | 추가·함량 보완 |
| [파로자트씨알](https://www.health.kr/drug/2021062400005) | 파로자트씨알정12.5mg | 파록세틴염산염수화물 ( Paroxetine Hydrochloride Hydrate ) 14.25 mg ( 파록세틴으로서 12.5mg ) | 장용성서방정 | 한림제약 | 검증·유지/첫 등장 정리 |
| [75 ㎎](https://www.health.kr/drug/A11ABBBBB1493) | 이팩사엑스알서방캡슐75mg | 벤라팍신염산염 ( Venlafaxine Hydrochloride ) 84.85 mg ( 벤라팍신으로서 75mg ) | 서방캡슐 | 비아트리스코리아 | 추가·함량 보완 |
| [이팩사 XR](https://www.health.kr/drug/A11ADDDDD0700) | 이팩사엑스알서방캡슐37.5mg | 벤라팍신염산염 ( Venlafaxine Hydrochloride ) 42.43 mg ( 벤라팍신으로서 37.5mg ) | 서방캡슐 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [야즈](https://health.kr/drug/A11AKP08G3788) | 야즈정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [임플라논 엔엑스티](https://www.health.kr/drug/A11AIIIII0018) | 임플라논엔엑스티이식제 | 에토노게스트렐 ( Etonogestrel ) 68 mg/Inplant | 이식제 | 한국오가논 | 검증·유지/첫 등장 정리 |
| [루피어데포 3.75 ㎎](https://www.health.kr/drug/A11AOOOOO3095) | 루피어데포주3.75mg | 류프로렐린아세트산염 ( Leuprolide Acetate ) 3.75 mg | 주사제 | 대웅제약 | 검증·유지/첫 등장 정리 |
| [졸라덱스데포](https://www.health.kr/drug/A11ACCCCC0529) | 졸라덱스데포주사 | 고세렐린아세트산염 ( Goserelin Acetate ) 3.78 mg | 주사제 | 한국아스트라제네카 | 검증·유지/첫 등장 정리 |
| [아나프록스](https://www.health.kr/drug/A11ABBBBB2070) | 아나프록스정 | 나프록센나트륨 ( Naproxen Sodium ) 275 mg | 정제 | 종근당 | 검증·유지/첫 등장 정리 |
| [부루펜](https://www.health.kr/drug/A11A0500A0131) | 부루펜정400mg | 이부프로펜 ( Ibuprofen ) 400 mg | 정제 | 삼일제약 | 추가·함량 보완 |
| [타이레놀](https://www.health.kr/drug/2021082400002) | 타이레놀정500mg | 아세트아미노펜 ( Acetaminophen ) 500 mg | 정제 | 한국존슨앤드존슨판매 | 추가·함량 보완 |
| [ER](https://www.health.kr/drug/2022020300026) | 타이레놀8시간이알서방정 | 1정 중 - 속방층 아세트아미노펜 ( Acetaminophen ) 325 mg 1정 중 - 서방층 아세트아미노펜 ( Acetaminophen ) 325 mg | 서방정 | 한국존슨앤드존슨판매 | 추가·함량 보완 |
| [프리페민](https://www.health.kr/drug/2013061000010) | 프리페민정 | 아그누스카스투스열매60%에탄올연조엑스(6~12→1)ㆍ콜로이드성이산화규소혼합물(1:1) ( Agnus Castus Fruit 60% Ethanol Soft Ext.(6~12→1)ㆍColloidal Silicon Dioxide Mixture(1:1) ) 40 mg ( 아그누스카스투스열매60%에탄올연조엑스(6~12→1)로서 20mg ) | 정제 | 종근당 | 검증·유지/첫 등장 정리 |
| [자낙스](https://www.health.kr/drug/A11ABBBBB0920) | 자낙스정0.25mg | 알프라졸람 ( Alprazolam ) 0.25 mg | 정제 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [알닥톤](https://www.health.kr/drug/A11AOOOOO3515) | 알닥톤필름코팅정25mg | 스피로노락톤 ( Spironolactone ) 25 mg | 정제 | 한국화이자제약 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [졸로푸트정·50 ㎎](https://www.health.kr/drug/A11A0310A0239) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [야즈정·drospirenone 3 ㎎/ethinyl estradiol 0.02 ㎎](https://health.kr/drug/A11AKP08G3788) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [아나프록스정·275 ㎎](https://www.health.kr/drug/A11ABBBBB2070) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 렉사프로 10·20 ㎎, 졸로푸트 50·100 ㎎, 파로자트씨알 12.5·25 ㎎, 이팩사 XR 37.5·75 ㎎을 각각 연결.
- 세로자트 10 ㎎은 실제 20 ㎎ 정제 함량으로 연결; 10 ㎎ 품목을 임의 생성하지 않음.
- 졸로푸트 150 ㎎·이팩사 XR 150 ㎎ 등 투여량은 확인된 제품 조합과 구분.
- 부루펜 본문 링크는 명시된 400 ㎎ 용량에 맞는 400 ㎎ 제품으로 변경.
- 아나프록스 초회 550 ㎎은 275 ㎎ 정제 2정이며 처방례 링크는 275 ㎎ 유지.

- 미적용·확인 필요: 프리페민: 본문은 건조 추출물, 약학정보원 성분명은 연조엑스로 표기되어 제형 표현 대조가 필요함. 임상 문구는 수정하지 않음.

## 128장 — 128_-dysmenorrhea.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [타이레놀](https://www.health.kr/drug/2021082400002) | 타이레놀정500mg | 아세트아미노펜 ( Acetaminophen ) 500 mg | 정제 | 한국존슨앤드존슨판매 | 추가·함량 보완 |
| [ER](https://www.health.kr/drug/2022020300026) | 타이레놀8시간이알서방정 | 1정 중 - 속방층 아세트아미노펜 ( Acetaminophen ) 325 mg 1정 중 - 서방층 아세트아미노펜 ( Acetaminophen ) 325 mg | 서방정 | 한국존슨앤드존슨판매 | 추가·함량 보완 |
| [400 ㎎](https://www.health.kr/drug/A11A0500A0131) | 부루펜정400mg | 이부프로펜 ( Ibuprofen ) 400 mg | 정제 | 삼일제약 | 추가·함량 보완 |
| [부루펜 200 ㎎](https://health.kr/drug/A11A0500A0097) | 부루펜정200mg | 이부프로펜 ( Ibuprofen ) 200 mg | 정제 | 삼일제약 | 검증·유지/첫 등장 정리 |
| [아나프록스 275 ㎎](https://www.health.kr/drug/A11ABBBBB2070) | 아나프록스정 | 나프록센나트륨 ( Naproxen Sodium ) 275 mg | 정제 | 종근당 | 검증·유지/첫 등장 정리 |
| [야즈](https://www.health.kr/drug/A11AKP08G3788) | 야즈정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [야스민](https://www.health.kr/drug/A11AKP08F0334) | 야스민정 | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [미레나](https://www.health.kr/drug/A11ABBBBB1200) | 미레나20μg/일 | 레보노르게스트렐 ( Levonorgestrel ) 52 mg | 이식제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [부루펜정·200 ㎎](https://health.kr/drug/A11A0500A0097) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [야즈정·drospirenone 3 ㎎/ethinyl estradiol 0.02 ㎎](https://health.kr/drug/A11AKP08G3788) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [부루펜정·400 ㎎](https://www.health.kr/drug/A11A0500A0131) · [야즈정·drospirenone 3 ㎎/ethinyl estradiol 0.02 ㎎](https://health.kr/drug/A11AKP08G3788) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 부루펜 200·400 ㎎을 각각 연결하되 처방례 1의 200 ㎎ 2정과 처방례 3의 400 ㎎ 1정을 그대로 구분.
- 타이레놀 일반정 500 ㎎·ER 650 ㎎을 구분.
- 비잔은 참고문헌의 제품설명서에서만 언급되어 본문 약제 링크를 임의 추가하지 않음.

## 129장 — 129_-abnormal-uterine-bleeding.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [야즈](https://www.health.kr/drug/A11AKP08G3788) | 야즈정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [클래라](https://www.health.kr/drug/2012042300003) | 클래라정 | 어두운 노란색 정제 에스트라디올발레레이트 ( Estradiol Valerate ) 3 mg 분홍색 정제 에스트라디올발레레이트 ( Estradiol Valerate ) 2 mg 갈색정제 에스트라디올발레레이트 ( Estradiol Valerate ) 1 mg 분홍색 정제 디에노게스트(미분화) ( Dienogest ) 2 mg 밝은 노란색 정제 디에노게스트(미분화) ( Dienogest ) 3 mg 에스트라디올발레레이트 ( Estradiol Valerate ) 2 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [프로베라](https://www.health.kr/drug/A11ABBBBB1687) | 프로베라정10mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 10 mg | 정제 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [야스민](https://www.health.kr/drug/A11AKP08F0334) | 야스민정 | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [5](https://www.health.kr/drug/A11A3770A0075) | 프로베라정5mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 5 mg | 정제 | 한국화이자제약 | 추가·함량 보완 |
| [미레나](https://www.health.kr/drug/A11ABBBBB1200) | 미레나20μg/일 | 레보노르게스트렐 ( Levonorgestrel ) 52 mg | 이식제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [도란사민](https://www.health.kr/drug/A11ABBBBB1075) | 도란사민캡슐 | 트라넥삼산 ( Tranexamic Acid ) 250 mg | 경질캡슐 | 제일약품 | 검증·유지/첫 등장 정리 |
| [부루펜](https://www.health.kr/drug/A11A0500A0131) | 부루펜정400mg | 이부프로펜 ( Ibuprofen ) 400 mg | 정제 | 삼일제약 | 추가·함량 보완 |
| [아나프록스](https://www.health.kr/drug/A11ABBBBB2070) | 아나프록스정 | 나프록센나트륨 ( Naproxen Sodium ) 275 mg | 정제 | 종근당 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [부루펜정·200 ㎎](https://www.health.kr/drug/A11A0500A0097) · [도란사민캡슐·250 ㎎](https://www.health.kr/drug/A11ABBBBB1075) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [야즈정·drospirenone 3 ㎎/EE 0.02 ㎎](https://www.health.kr/drug/A11AKP08G3788) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [프로베라정·10 ㎎](https://www.health.kr/drug/A11ABBBBB1687) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [프로베라정·10 ㎎](https://www.health.kr/drug/A11ABBBBB1687) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [클래라정·estradiol valerate/dienogest 3/0→2/2→2/3→1/0 ㎎ 및 위약](https://www.health.kr/drug/2012042300003) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 프로베라 5·10 ㎎을 각각 연결. 고용량 MPA 20 ㎎은 10 ㎎ 정제 2정이므로 처방례는 실제 10 ㎎ 제품 링크 유지.
- 부루펜 본문은 400 ㎎ 제품, 처방례는 실제 200 ㎎ 정제 2정 제품으로 구분.
- 클래라 처방례의 약제 정보에 다상성 성분 함량과 위약을 명시.

## 130장 — 130_-amenorrhea.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [미레나](https://www.health.kr/drug/A11ABBBBB1200) | 미레나20μg/일 | 레보노르게스트렐 ( Levonorgestrel ) 52 mg | 이식제 | 바이엘코리아 | 추가·함량 보완 |
| [씬지로이드](https://www.health.kr/drug/2019052200017) | 씬지로이드정0.025mg | 레보티록신나트륨수화물 ( Levothyroxine Sodium Hydrate ) 25 μg | 정제 | 부광약품 | 검증·유지/첫 등장 정리 |
| [카버락틴](https://health.kr/drug/2015020600007) | 카버락틴정0.25mg | 카베르골린 ( Cabergoline ) 0.25 mg | 정제 | 동구바이오제약 | 검증·유지/첫 등장 정리 |
| [프로베라](https://www.health.kr/drug/A11A3770A0075) | 프로베라정5mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 5 mg | 정제 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11ABBBBB1687) | 프로베라정10mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 10 mg | 정제 | 한국화이자제약 | 추가·함량 보완 |
| [야스민](https://www.health.kr/drug/A11AKP08F0334) | 야스민정 | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [프로베라정·5 ㎎](https://www.health.kr/drug/A11A3770A0075) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [야스민정·drospirenone 3 ㎎/EE 0.03 ㎎](https://www.health.kr/drug/A11AKP08F0334) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [프로베라정·5 ㎎](https://www.health.kr/drug/A11A3770A0075) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [씬지로이드정·25 ㎍](https://www.health.kr/drug/2019052200017) | 품목·함량·제형 대조 및 링크 열림 확인 |

처방례 3 주석의 [에스트레바겔](https://www.health.kr/drug/A11ABBBBB0522)은 성분·함량(estradiol 1 ㎎/g, 1회 펌프당 0.5 ㎎)·겔제·제조사 삼오제약을 대조하고 링크를 유지했습니다. 처방 코드블록은 제형·용량을 개별 결정하는 estradiol 성분 처방이므로 약제 정보 줄에 임의 상품을 추가하지 않았습니다.

### 용량·품목 구분 및 유의 사항

- 프로베라 5·10 ㎎을 구분하고 처방례의 5 ㎎ 2정은 실제 5 ㎎ 제품으로 연결.
- 카버락틴 주당 총량 0.5 ㎎과 1회 0.25 ㎎을 구분하며 0.25 ㎎ 정제 링크 유지.
- 처방례 3의 경피 estradiol은 제형·용량을 개별 결정하는 성분명 처방이므로 임의 상품을 약제 정보 줄에 추가하지 않음. 기존 주석의 에스트레바겔 제품 링크는 유지.

## 131장 — 131_-contraception.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [노레보원](https://www.health.kr/drug/A11APPPPP0711) | 노레보원정 | 레보노르게스트렐 ( Levonorgestrel ) 1.5 mg | 정제 | 현대약품 | 검증·유지/첫 등장 정리 |
| [엘라원](https://www.health.kr/drug/2011071500001) | 엘라원정 | 울리프리스탈아세테이트 ( Ulipristal Acetate ) 30 mg | 정제 | 현대약품 | 검증·유지/첫 등장 정리 |
| [야스민](https://www.health.kr/drug/A11AKP08F0334) | 야스민정 | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [야즈](https://www.health.kr/drug/A11AKP08G3788) | 야즈정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [머시론](https://www.health.kr/drug/A11ABBBBB2499) | 머시론정 | 데소게스트렐 ( Desogestrel ) 0.15 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg | 정제 | 알보젠코리아 | 검증·유지/첫 등장 정리 |
| [멜리안](https://www.health.kr/drug/A11AKP08G3641) | 멜리안정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 게스토덴 ( Gestodene ) 0.075 mg | 정제 | 동아제약 | 검증·유지/첫 등장 정리 |
| [센스리베](https://www.health.kr/drug/2012090700001) | 센스리베정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 게스토덴 ( Gestodene ) 0.075 mg | 정제 | 광동제약 | 검증·유지/첫 등장 정리 |
| [미니보라30](https://www.health.kr/drug/A11ADDDDD0662) | 미니보라30 | 레보노르게스트렐 ( Levonorgestrel ) 0.15 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 동아제약 | 검증·유지/첫 등장 정리 |
| [슬린다](https://www.health.kr/drug/2024081400006) | 슬린다정4mg | 드로스피레논 ( Drospirenone ) 4 mg | 정제 | 현대약품 | 검증·유지/첫 등장 정리 |
| [미레나](https://www.health.kr/drug/A11ABBBBB1200) | 미레나20μg/일 | 레보노르게스트렐 ( Levonorgestrel ) 52 mg | 이식제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [카일리나](https://www.health.kr/drug/2017051900002) | 카일리나19.5mg | 레보노르게스트렐 ( Levonorgestrel ) 19.5 mg | 이식제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [제이디스](https://www.health.kr/drug/2013092300002) | 제이디스13.5mg | 1세트 중 레보노르게스트렐 ( Levonorgestrel ) 13.5 mg | 이식제 | 바이엘코리아 | 검증·유지/첫 등장 정리 |
| [임플라논엔엑스티](https://www.health.kr/drug/A11AIIIII0018) | 임플라논엔엑스티이식제 | 에토노게스트렐 ( Etonogestrel ) 68 mg/Inplant | 이식제 | 한국오가논 | 검증·유지/첫 등장 정리 |
| [노원질좌제](https://www.health.kr/drug/A11A2140A0094) | 노원질좌제100mg | 노녹시놀9 ( Nonoxynol-9 ) 100 mg | 좌제 | 한미약품 | 검증·유지/첫 등장 정리 |
| [프로베라](https://www.health.kr/drug/A11A3770A0075) | 프로베라정5mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 5 mg | 정제 | 한국화이자제약 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11ABBBBB1687) | 프로베라정10mg | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 10 mg | 정제 | 한국화이자제약 | 추가·함량 보완 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [야스민정·EE 0.03 ㎎/drospirenone 3 ㎎](https://www.health.kr/drug/A11AKP08F0334) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [슬린다정·4 ㎎](https://www.health.kr/drug/2024081400006) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [미레나·52 ㎎](https://www.health.kr/drug/A11ABBBBB1200) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [노레보원정·1.5 ㎎](https://www.health.kr/drug/A11APPPPP0711) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [엘라원정·30 ㎎](https://www.health.kr/drug/2011071500001) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 6 | [야스민정·EE 0.03 ㎎/drospirenone 3 ㎎](https://www.health.kr/drug/A11AKP08F0334) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 알고리듬 주석·주의사항 등 본문에서 먼저 언급된 노레보원·엘라원·야스민·야즈·LNG-IUD의 링크를 첫 등장으로 이동.
- 프로베라 5·10 ㎎을 각각 연결.
- 핵심 복약 지도에만 등장하는 유로시트라케이는 해당 절 유지 지시에 따라 변경하지 않음.

- 미적용·확인 필요: 노바-티는 의료기기로 약학정보원 의약품 품목을 임의 연결하지 않음.
- 미적용·확인 필요: Lunelle/Cyclofem, Xulane, Twirla, Annovera 등 해외 제품 예시는 정확한 약학정보원 의약품 품목을 확인하지 못해 링크하지 않음.
- 미적용·확인 필요: 프리모루트엔은 원고에서 현행 공급 미확인으로 설명된 과거 제품이며 확인되지 않은 상세 링크를 만들지 않음.

## 132장 — 132_-sexual-dysfunction.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [비아그라](https://www.health.kr/drug/A11ABBBBB0961) | 비아그라정50mg | 실데나필시트르산염 ( Sildenafil Citrate ) 70.225 mg ( 실데나필로서 50mg ) | 정제 | 비아트리스코리아 | 검증·유지/첫 등장 정리 |
| [100 ㎎](https://www.health.kr/drug/A11ABBBBB2544) | 비아그라정100mg | 실데나필시트르산염 ( Sildenafil Citrate ) 140.45 mg ( 실데나필로서 100mg ) | 정제 | 비아트리스코리아 | 추가·함량 보완 |
| [시알리스](https://www.health.kr/drug/A11AKP08G3782) | 시알리스정5mg | 타다라필 ( Tadalafil ) 5 mg | 정제 | 지피테라퓨틱스코리아 | 검증·유지/첫 등장 정리 |
| [10 ㎎](https://www.health.kr/drug/A11ALLLLL0053) | 시알리스정10mg | 타다라필 ( Tadalafil ) 10 mg | 정제 | 지피테라퓨틱스코리아 | 추가·함량 보완 |
| [20 ㎎](https://www.health.kr/drug/A11ALLLLL0051) | 시알리스정20mg | 타다라필 ( Tadalafil ) 20 mg | 정제 | 지피테라퓨틱스코리아 | 추가·함량 보완 |
| [엠빅스](https://www.health.kr/drug/cnjx5ar2p1b5f) | 엠빅스정50mg | 미로데나필염산염 ( Mirodenafil Hydrochloride ) 56.9 mg ( 미로데나필로서 50mg ) | 정제 | 에스케이케미칼 | 검증·유지/첫 등장 정리 |
| [자이데나](https://www.health.kr/drug/2010100800003) | 자이데나정50mg | 유데나필 ( Udenafil ) 50 mg | 정제 | 동아에스티 | 검증·유지/첫 등장 정리 |
| [100 ㎎](https://www.health.kr/drug/A11AOOOOO7701) | 자이데나정100mg | 유데나필 ( Udenafil ) 100 mg | 정제 | 동아에스티 | 추가·함량 보완 |
| [200 ㎎](https://www.health.kr/drug/A11AOOOOO9244) | 자이데나정200mg | 유데나필 ( Udenafil ) 200 mg | 정제 | 동아에스티 | 추가·함량 보완 |
| [75 ㎎](https://www.health.kr/drug/2013101600001) | 자이데나정75mg | 유데나필 ( Udenafil ) 75 mg | 정제 | 동아에스티 | 추가·함량 보완 |
| [야일라·10 ㎎](https://www.health.kr/drug/2020041300006) | 야일라정10mg | 바데나필염산염수화물 ( Vardenafil Hydrochloride Hydrate ) 11.852 mg ( 바데나필로서 10mg ) | 정제 | 종근당 | 추가·함량 보완 |
| [야일라·20 ㎎](https://www.health.kr/drug/2020041300007) | 야일라정20mg | 바데나필염산염수화물 ( Vardenafil Hydrochloride Hydrate ) 23.705 mg ( 바데나필로서 20mg ) | 정제 | 종근당 | 추가·함량 보완 |
| [엠빅스에스·50 ㎎, 구강붕해필름](https://www.health.kr/drug/2011120200002) | 엠빅스에스구강붕해필름50mg | 미로데나필 ( Mirodenafil ) 50 mg | 구강용해필름제 | 에스케이케미칼 | 추가·함량 보완 |
| [엠빅스에스·100 ㎎, 구강붕해필름](https://www.health.kr/drug/2012120300016) | 엠빅스에스구강붕해필름100mg | 미로데나필 ( Mirodenafil ) 100 mg | 구강용해필름제 | 에스케이케미칼 | 추가·함량 보완 |
| [나테스토나잘겔](https://www.health.kr/drug/2018060700006) | 나테스토나잘겔 | 테스토스테론 ( Testosterone ) 45 mg/g | 겔제 | 현대약품 | 검증·유지/첫 등장 정리 |
| [네비도](https://www.health.kr/drug/2015121800015) | 네비도주사바이알 | 테스토스테론운데카노에이트 ( Testosterone Undecanoate ) 250 mg/mL | 주사제 | 에스케이케미칼 | 검증·유지/첫 등장 정리 |
| [엠라](https://www.health.kr/drug/A11AMMMMM2194) | 엠라5%크림 | 리도카인 ( Lidocaine ) 25 mg/g 프릴로카인 ( Prilocaine ) 25 mg/g | 크림 | 타나베파마코리아 | 검증·유지/첫 등장 정리 |
| [프릴리지](https://www.health.kr/drug/2009090700540) | 프릴리지정30mg | 다폭세틴염산염 ( Dapoxetine Hydrochloride ) 33.6 mg ( 다폭세틴으로서 30mg ) | 정제 | 한국메나리니 | 검증·유지/첫 등장 정리 |
| [60 ㎎](https://www.health.kr/drug/2009090700541) | 프릴리지정60mg | 다폭세틴염산염 ( Dapoxetine Hydrochloride ) 67.2 mg ( 다폭세틴으로서 60mg ) | 정제 | 한국메나리니 | 추가·함량 보완 |
| [네노마](https://www.health.kr/drug/2013032100009) | 네노마정15mg | 클로미프라민염산염 ( Clomipramine Hydrochloride ) 15 mg | 정제 | 휴온스 | 검증·유지/첫 등장 정리 |
| [유로시트라케이](https://www.health.kr/drug/A11AOOOOO9528) | 유로시트라케이10mEq서방정 | 시트르산칼륨수화물 ( Potassium Citrate Hydrate ) 1080 mg | 서방정 | 한국팜비오 | 추가·함량 보완 |
| [타이레놀](https://www.health.kr/drug/2022020300026) | 타이레놀8시간이알서방정 | 1정 중 - 속방층 아세트아미노펜 ( Acetaminophen ) 325 mg 1정 중 - 서방층 아세트아미노펜 ( Acetaminophen ) 325 mg | 서방정 | 한국존슨앤드존슨판매 | 추가·함량 보완 |
| [리비알](https://www.health.kr/drug/2009092300016) | 리비알정 | 티볼론 ( Tibolone ) 2.5 mg | 정제 | 한국오가논 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [비아그라정·50 ㎎](https://www.health.kr/drug/A11ABBBBB0961) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [팔팔츄정·25 ㎎](https://www.health.kr/drug/2012060100006) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [시알리스정·5 ㎎](https://www.health.kr/drug/A11AKP08G3782) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [나테스토나잘겔·45 ㎎/g, 5.5 ㎎/펌프](https://www.health.kr/drug/2018060700006) · [시알리스정·5 ㎎](https://www.health.kr/drug/A11AKP08G3782) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [프릴리지정·30 ㎎](https://www.health.kr/drug/2009090700540) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 6 | [엠라5%크림·리도카인 25 ㎎/g/프릴로카인 25 ㎎/g](https://www.health.kr/drug/A11AMMMMM2194) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 7 | [시알리스정·5 ㎎](https://www.health.kr/drug/A11AKP08G3782) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 8 | [네노마정·15 ㎎](https://www.health.kr/drug/2013032100009) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 사용자가 제공한 야일라 10·20 ㎎ 정제와 엠빅스에스 50·100 ㎎ 구강붕해필름을 제품별 상세 정보로 추가. 레비트라와 엠빅스의 기존 상품명·본문 용량은 유지하고 다른 상품·제형 링크를 기존 상품명에 붙이지 않음.
- 시알리스 5·10·20 ㎎, 자이데나 50·75·100·200 ㎎, 프릴리지 30·60 ㎎을 각각 연결.
- 나테스토나잘겔은 45 ㎎/g 및 5.5 ㎎/펌프, 네비도는 1,000 ㎎/4 ㎖ 바이알로 대조.
- 팔팔츄정 25 ㎎ 처방례는 실제 저작정 품목으로 연결.
- 상품명 없는 SSRI·조제약 등에는 임의 상품을 추가하지 않음.

- 미적용·확인 필요: 레비트라 5·10·20 ㎎: 검색에서 과거 약학정보원 품목 기록은 확인했으나 의약품 상세 페이지는 모두 HTTP 404로 열리지 않아 해당 상품명에는 미적용. 제공된 야일라 10·20 ㎎은 실제 상품명으로 별도 연결.
- 미적용·확인 필요: 엠빅스 100 ㎎: 검색에서 품목 기록은 확인했으나 의약품 상세 페이지는 HTTP 404로 열리지 않아 미적용. 50 ㎎ 정제 링크는 검증하여 유지하고, 제공된 엠빅스에스 필름 50·100 ㎎은 별도 상품명·제형으로 연결.
- 미적용·확인 필요: 비아그라 25 ㎎: 상세 페이지에 2026-04-01 품목 취소일이 표시되어 현행 제품 링크로 추가하지 않음. 본문의 sildenafil 25 ㎎ 용량과 처방례 팔팔츄정 25 ㎎은 변경하지 않음.

## 133장 — 133_-urolithiasis.md

### 본문 적용

| 표시 문구 | 확인 제품 | 성분·함량 | 제형 | 제조·수입사 | 처리 |
|---|---|---|---|---|---|
| [한미탐스](https://www.health.kr/drug/2016010500011) | 한미탐스캡슐0.4mg | 탐스로신염산염 ( Tamsulosin Hydrochloride ) 0.4 mg | 서방캡슐 | 한미약품 | 검증·유지/첫 등장 정리 |
| [400 ㎎](https://www.health.kr/drug/A11A0500A0131) | 부루펜정400mg | 이부프로펜 ( Ibuprofen ) 400 mg | 정제 | 삼일제약 | 추가·함량 보완 |
| [부루펜](https://www.health.kr/drug/A11A0500A0097) | 부루펜정200mg | 이부프로펜 ( Ibuprofen ) 200 mg | 정제 | 삼일제약 | 검증·유지/첫 등장 정리 |
| [애니펜](https://www.health.kr/drug/A11AEEEEE0492) | 애니펜정300mg | 덱시부프로펜 ( Dexibuprofen ) 300 mg | 정제 | 안국약품 | 검증·유지/첫 등장 정리 |
| [낙센](https://www.health.kr/drug/A11A0120A0286) | 낙센정 | 나프록센 ( Naproxen ) 250 mg | 정제 | 종근당 | 검증·유지/첫 등장 정리 |
| [마이폴](https://www.health.kr/drug/A11AOOOOO1290) | 마이폴캡슐 | 아세트아미노펜 ( Acetaminophen ) 250 mg 이부프로펜 ( Ibuprofen ) 200 mg 코데인인산염수화물 ( Codeine Phosphate Hydrate ) 10 mg | 경질캡슐 | 성원애드콕제약 | 검증·유지/첫 등장 정리 |
| [타이레놀8시간이알](https://www.health.kr/drug/2022020300026) | 타이레놀8시간이알서방정 | 1정 중 - 속방층 아세트아미노펜 ( Acetaminophen ) 325 mg 1정 중 - 서방층 아세트아미노펜 ( Acetaminophen ) 325 mg | 서방정 | 한국존슨앤드존슨판매 | 검증·유지/첫 등장 정리 |
| [하이코돈](https://www.health.kr/drug/2012040200006) | 하이코돈정5mg | 아세트아미노펜 ( Acetaminophen ) 325 mg 히드로코돈타르타르산염 ( Hydrocodone Tartrate ) 5 mg | 정제 | 비씨월드제약 | 검증·유지/첫 등장 정리 |
| [다이크로짇](https://www.health.kr/drug/A11A0450A0076) | 다이크로짇정 | 히드로클로로티아지드 ( Hydrochlorothiazide ) 25 mg | 정제 | 유한양행 | 검증·유지/첫 등장 정리 |
| [유로시트라케이](https://www.health.kr/drug/A11AOOOOO9528) | 유로시트라케이10mEq서방정 | 시트르산칼륨수화물 ( Potassium Citrate Hydrate ) 1080 mg | 서방정 | 한국팜비오 | 검증·유지/첫 등장 정리 |
| [슬린다](https://www.health.kr/drug/2024081400006) | 슬린다정4mg | 드로스피레논 ( Drospirenone ) 4 mg | 정제 | 현대약품 | 추가·함량 보완 |
| [야스민](https://www.health.kr/drug/A11AKP08F0334) | 야스민정 | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 | 추가·함량 보완 |
| [야즈](https://www.health.kr/drug/A11AKP08G3788) | 야즈정 | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 | 추가·함량 보완 |
| [자이로릭](https://www.health.kr/drug/A11A0500A0069) | 자이로릭정 | 알로푸리놀 ( Allopurinol ) 100 mg | 정제 | 삼일제약 | 검증·유지/첫 등장 정리 |

### 처방례 적용

| 처방례 | 코드블록 바로 아래의 약제 정보 | 확인 |
|---|---|---|
| 1 | [애니펜정·300 ㎎](https://www.health.kr/drug/A11AEEEEE0492) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 2 | [한미탐스캡슐·0.4 ㎎](https://www.health.kr/drug/2016010500011) · [애니펜정·300 ㎎](https://www.health.kr/drug/A11AEEEEE0492) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 3 | [마이폴캡슐·acetaminophen 250 ㎎/ibuprofen 200 ㎎/codeine phosphate hydrate 10 ㎎](https://www.health.kr/drug/A11AOOOOO1290) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 4 | [하이코돈정·hydrocodone tartrate 5 ㎎/acetaminophen 325 ㎎](https://www.health.kr/drug/2012040200006) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 5 | [다이크로짇정·25 ㎎](https://www.health.kr/drug/A11A0450A0076) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 6 | [유로시트라케이10mEq서방정·10 mEq](https://www.health.kr/drug/A11AOOOOO9528) | 품목·함량·제형 대조 및 링크 열림 확인 |
| 7 | [유로시트라케이10mEq서방정·10 mEq](https://www.health.kr/drug/A11AOOOOO9528) | 품목·함량·제형 대조 및 링크 열림 확인 |

### 용량·품목 구분 및 유의 사항

- 부루펜 200·400 ㎎을 각각 연결.
- 마이폴과 타이레놀8시간이알은 본문 첫 언급으로 링크 이동.
- 상호작용 설명의 슬린다·야스민·야즈 첫 언급을 각각 실제 제품으로 연결.
- 낙센 500 ㎎ 투여량은 실제 250 ㎎ 정제 2정과 구분하여 기존 낙센정 링크 유지. 이름이 다른 낙센에프를 임의로 대입하지 않음.
- 자이로릭 100~300 ㎎/일은 총 투여량 범위이므로 확인된 100 ㎎ 정제 링크 유지.
- 유로시트라케이 20 mEq/회는 10 mEq 정제 2정으로 구분하며 처방례 링크는 실제 10 mEq 제품으로 유지.

## 처방례 품목 대조 목록

처방례에서 사용한 품목의 제조사·성분·제형을 중복 없이 정리했습니다. 각 처방례의 제품 연결은 위 표에서 확인할 수 있습니다.

| 품목 | 성분·함량 | 제형 | 제조·수입사 |
|---|---|---|---|
| [나테스토나잘겔](https://www.health.kr/drug/2018060700006) | 테스토스테론 ( Testosterone ) 45 mg/g | 겔제 | 현대약품 |
| [네노마정15mg](https://www.health.kr/drug/2013032100009) | 클로미프라민염산염 ( Clomipramine Hydrochloride ) 15 mg | 정제 | 휴온스 |
| [노레보원정](https://www.health.kr/drug/A11APPPPP0711) | 레보노르게스트렐 ( Levonorgestrel ) 1.5 mg | 정제 | 현대약품 |
| [다이크로짇정](https://www.health.kr/drug/A11A0450A0076) | 히드로클로로티아지드 ( Hydrochlorothiazide ) 25 mg | 정제 | 유한양행 |
| [도란사민캡슐](https://www.health.kr/drug/A11ABBBBB1075) | 트라넥삼산 ( Tranexamic Acid ) 250 mg | 경질캡슐 | 제일약품 |
| [디트루시톨SR캡슐4mg](https://www.health.kr/drug/A11AOOOOO3053) | 톨터로딘-L-타르타르산염 ( Tolterodine L-Tartrate ) 4 mg | 서방캡슐 | 비아트리스코리아 |
| [마이폴캡슐](https://www.health.kr/drug/A11AOOOOO1290) | 아세트아미노펜 ( Acetaminophen ) 250 mg 이부프로펜 ( Ibuprofen ) 200 mg 코데인인산염수화물 ( Codeine Phosphate Hydrate ) 10 mg | 경질캡슐 | 성원애드콕제약 |
| [미레나20μg/일](https://www.health.kr/drug/A11ABBBBB1200) | 레보노르게스트렐 ( Levonorgestrel ) 52 mg | 이식제 | 바이엘코리아 |
| [베시케어정5mg](https://www.health.kr/drug/A11APPPPP1278) | 솔리페나신숙신산염 ( Solifenacin Succinate ) 5 mg | 정제 | 한국아스텔라스제약 |
| [베오바정50mg](https://www.health.kr/drug/2022110100005) | 비베그론 ( Vibegron ) 50 mg | 정제 | 제일약품 |
| [베타미가서방정50mg](https://www.health.kr/drug/2014010200015) | 미라베그론 ( Mirabegron ) 50 mg | 서방정 | 한국아스텔라스제약 |
| [부루펜정200mg](https://www.health.kr/drug/A11A0500A0097) | 이부프로펜 ( Ibuprofen ) 200 mg | 정제 | 삼일제약 |
| [부루펜정400mg](https://www.health.kr/drug/A11A0500A0131) | 이부프로펜 ( Ibuprofen ) 400 mg | 정제 | 삼일제약 |
| [비아그라정50mg](https://www.health.kr/drug/A11ABBBBB0961) | 실데나필시트르산염 ( Sildenafil Citrate ) 70.225 mg ( 실데나필로서 50mg ) | 정제 | 비아트리스코리아 |
| [슬린다정4mg](https://www.health.kr/drug/2024081400006) | 드로스피레논 ( Drospirenone ) 4 mg | 정제 | 현대약품 |
| [시알리스정5mg](https://www.health.kr/drug/A11AKP08G3782) | 타다라필 ( Tadalafil ) 5 mg | 정제 | 지피테라퓨틱스코리아 |
| [씬지로이드정0.025mg](https://www.health.kr/drug/2019052200017) | 레보티록신나트륨수화물 ( Levothyroxine Sodium Hydrate ) 25 μg | 정제 | 부광약품 |
| [아나프록스정](https://www.health.kr/drug/A11ABBBBB2070) | 나프록센나트륨 ( Naproxen Sodium ) 275 mg | 정제 | 종근당 |
| [아보다트연질캡슐0.5mg](https://www.health.kr/drug/A11AOOOOO4032) | 두타스테리드 ( Dutasteride ) 0.5 mg | 연질캡슐 | 글락소스미스클라인 |
| [애니펜정300mg](https://www.health.kr/drug/A11AEEEEE0492) | 덱시부프로펜 ( Dexibuprofen ) 300 mg | 정제 | 안국약품 |
| [야스민정](https://www.health.kr/drug/A11AKP08F0334) | 드로스피레논 ( Drospirenone ) 3 mg 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.03 mg | 정제 | 바이엘코리아 |
| [야즈정](https://www.health.kr/drug/A11AKP08G3788) | 에티닐에스트라디올 ( Ethinyl Estradiol ) 0.02 mg 드로스피레논 ( Drospirenone ) 3 mg | 정제 | 바이엘코리아 |
| [엘라원정](https://www.health.kr/drug/2011071500001) | 울리프리스탈아세테이트 ( Ulipristal Acetate ) 30 mg | 정제 | 현대약품 |
| [엠라5%크림](https://www.health.kr/drug/A11AMMMMM2194) | 리도카인 ( Lidocaine ) 25 mg/g 프릴로카인 ( Prilocaine ) 25 mg/g | 크림 | 타나베파마코리아 |
| [유로시트라케이10mEq서방정](https://www.health.kr/drug/A11AOOOOO9528) | 시트르산칼륨수화물 ( Potassium Citrate Hydrate ) 1080 mg | 서방정 | 한국팜비오 |
| [자트랄엑스엘정10mg](https://www.health.kr/drug/A11AJJJJJ0228) | 알푸조신염산염 ( Alfuzosin Hydrochloride ) 10 mg | 서방정 | 한독 |
| [졸로푸트정50mg](https://www.health.kr/drug/A11A0310A0239) | 설트랄린염산염 ( Sertraline Hydrochloride ) 55.95 mg ( 설트랄린으로서 50mg ) | 정제 | 비아트리스코리아 |
| [클래라정](https://www.health.kr/drug/2012042300003) | 어두운 노란색 정제 에스트라디올발레레이트 ( Estradiol Valerate ) 3 mg 분홍색 정제 에스트라디올발레레이트 ( Estradiol Valerate ) 2 mg 갈색정제 에스트라디올발레레이트 ( Estradiol Valerate ) 1 mg 분홍색 정제 디에노게스트(미분화) ( Dienogest ) 2 mg 밝은 노란색 정제 디에노게스트(미분화) ( Dienogest ) 3 mg 에스트라디올발레레이트 ( Estradiol Valerate ) 2 mg | 정제 | 바이엘코리아 |
| [트루패스구강붕해정8mg](https://www.health.kr/drug/2015050100116) | 실로도신 ( Silodosin ) 8 mg | 속붕해정(구강붕해정) | 제이더블유중외제약 |
| [팔팔츄정25mg](https://www.health.kr/drug/2012060100006) | 실데나필 ( Sildenafil ) 25 mg | 저작정(츄어블정) | 한미약품 |
| [프로베라정10mg](https://www.health.kr/drug/A11ABBBBB1687) | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 10 mg | 정제 | 한국화이자제약 |
| [프로베라정5mg](https://www.health.kr/drug/A11A3770A0075) | 메드록시프로게스테론아세테이트 ( Medroxyprogesterone Acetate ) 5 mg | 정제 | 한국화이자제약 |
| [프로스카정](https://www.health.kr/drug/A11ABBBBB0944) | 피나스테리드 ( Finasteride ) 5 mg | 정제 | 한국오가논 |
| [프릴리지정30mg](https://www.health.kr/drug/2009090700540) | 다폭세틴염산염 ( Dapoxetine Hydrochloride ) 33.6 mg ( 다폭세틴으로서 30mg ) | 정제 | 한국메나리니 |
| [플리바스정25mg](https://www.health.kr/drug/2011050200001) | 나프토피딜 ( Naftopidil ) 25 mg | 정제 | 동아에스티 |
| [하루날디정0.2mg](https://www.health.kr/drug/A11AOOOOO9776) | 탐스로신염산염 ( Tamsulosin Hydrochloride ) 0.2 mg | 속붕해정(구강붕해정) | 한국아스텔라스제약 |
| [하이코돈정5mg](https://www.health.kr/drug/2012040200006) | 아세트아미노펜 ( Acetaminophen ) 325 mg 히드로코돈타르타르산염 ( Hydrocodone Tartrate ) 5 mg | 정제 | 비씨월드제약 |
| [한미탐스캡슐0.4mg](https://www.health.kr/drug/2016010500011) | 탐스로신염산염 ( Tamsulosin Hydrochloride ) 0.4 mg | 서방캡슐 | 한미약품 |
