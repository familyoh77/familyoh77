# 무월경 Amenorrhea

## 분류 및 원인

1차성 무월경

* 정의 : 15세까지 초경이 없거나(15세까지 98%에서 초경 출현), 유방 발달 시작(thelarche) 후 3년(\~4년) 내 초경(menarche) 없음
* 빈도 ＜1%
* 원인 : 타고난 사춘기 지연, 염색체 이상(예: gonadal dysgenesis), hypogonadotropic hypogonadism, 생식기 발달 장애, transverse vaginal septum/imperforate hymen, pituitary Dz

#### 2차성 무월경

* 정의 : 초경 이후 3개월(\~6개월) 연속 월경 없음
* 빈도 5(3\~7)%
* 원인
  * physiologic : 임신/수유, 폐경
  * Hypothalamic Dz : 심한 비만, 영양 장애(예: 다이어트, IBD, 영양 흡수 장애, 소모성 질환), 심한 운동(스포츠 무월경), 우울, 스트레스
  * 내분비 질환 : 갑상선저하증, hyperprolactinemia, 비조절 당뇨병, 쿠싱증후군
  * 난소 질환 : 다낭성난소증후군, 난소 부전, 난소 종양
  * 약물 : 항우울제, 항정신병제, 화학요법, 피임제

## 진단

* 임신 배제
* BMI, 식이 습관, 육체적/정신적 스트레스, 병력

### 검사

* 대상 : ① 13세까지 유방 발달 등 2차 성징이 없거나 신장 하위 ≤3%, ② 15세까지 무월경
* 실험실 검사 : s/u-hCG, LH, FSH, prolactin, TSH, CBC, ESR
  * 선택 : hyperandrogenism 의심 시 testosterone, 17α hydroxyprogesterone; 염색체 이상 의심 시 karyotyping
* 영상 검사 : 골반 초음파, MRI(뇌, 골반)
* 복강경 검사, hysterosalpingogram

```mermaid
flowchart TD
    A["병력 확인 및 신체검사"] --> B["• 임신 검사<br>• serum LH, FSH, TSH, prolactin<br>• 적응증이 되는 경우 pelvic ultrasonography or 기타 실험실 검사"]

    B --> C["• 임신 검사 양성: 임신, 적절한 치료<br>• 비정상 TSH: 다른 TFT 시행, 갑상선 질환 치료<br>• 비정상 prolactin: 뇌 MRI(pituitary adenoma 배제); 약물 리뷰"]
    B --> D{"자궁 존재?"}

    %% 자궁 존재: Yes
    D -- yes --> E1["FSH & LH ↓"]
    D -- yes --> E2["normal FSH & LH*"]
    D -- yes --> E3["FSH & LH ↑"]

    E1 --> F1["기능성 hypothalamic 무월경(if 기력 저하),<br>체질적 사춘기 지연;<br>1차성 gonadotropin 분비 호르몬 결핍"]
    E2 --> F2["outflow tract 폐쇄;<br>정상 gonadotropin 수준의 다른 원인들"]
    E3 --> F3_1["1차성 난소 부전"] --> F3_2["karyotype 검사<br>(Turner syndrome, Y chromatin 존재)"]

    %% 자궁 존재: No
    D -- no --> G["karyotype; free & total testosterone"]

    G --> H1["46,XX, female-range testosterone"]
    G --> H2["46,XY, male-range testosterone"]

    H1 --> I1["Müllerian agenesis"]
    H2 --> I2["Androgen 불감성 증후군,<br>5α-reductase 결핍"]

    %% 주석
    FOOTNOTE["*명확한 진단을 위하여 필요시 1개월 후에 반복할 수 있음"]

    %% 스타일 정의
    classDef purple fill:#EAE8F8,stroke:#B0A3E0,color:#333
    classDef green fill:#E2F0D9,stroke:#A9D08E,color:#333
    classDef blue fill:#DDEBF7,stroke:#9BC2E6,color:#333
    classDef yellow fill:#FFF2CC,stroke:#FFE699,color:#333
    classDef red fill:#FCE4D6,stroke:#F4B08A,color:#333
    classDef note fill:none,stroke:none,color:#555,font-style:italic

    class A purple
    class B,G green
    class C blue
    class D,E1,E2,E3,H1,H2 yellow
    class F1,F2,F3_1,I1,I2 red
    class FOOTNOTE note
```

1차성 무월경의 진단\
Ref. Amenorrhea: A Systematic Approach to Diagnosis and Management. AFP. 2019;100(1). Fig 1.

```mermaid
flowchart TD
    A["병력 확인 및 신체검사, 피임제 등 약물 리뷰"] --> B["임신 검사; serum LH, FSH, TSH, prolactin;<br>적응증이 되는 경우<br>pelvic ultrasonography or 기타 실험실 검사"]

    B --> C["•임신 검사 양성 → 임신, 적절한 치료<br>•비정상 TSH → 다른 TFT 시행,<br>갑상선 질환 치료<br>•비정상 prolactin → 뇌 MRI(R/O<br>pituitary adenoma); 약물 리뷰"]
    B ----> D["정상 or 낮은<br>FSH or LH"]
    B --> E["높은 FSH & LH*"]

    E --> E_sub["•1개월 후 재검; estradiol 검사 고려<br>•1차성 난소 부전, 자연 폐경;<br>karyotype 검사(특히 저성장 시;<br>R/O Turner syndrome or variant)"]

    %% 정상 or 낮은 FSH or LH 하위 4개 분기
    D --> D1["잘못된 식습관, 과도한<br>운동, 불량한 영양 상태"]
    D --> D2["두개 내압 상승 증거<br>(두통, 구토, 시각변화)"]
    D --> D3["hyperandrogenism<br>증거"]
    D --> D4["산부인과적<br>시술 병력"]

    D1 --> D1_sub["기능성 hypothalamic<br>무월경(대부분),<br>만성 질환"]
    D2 --> D2_sub["뇌 MRI(R/O 종양)"]
    
    D3 --> D3_sub["testosterone,<br>DHEA-S,<br>17-hydroxy-<br>progesterone 검사"]
    
    D3_sub --> D3_1["17-OH-progesterone<br>증가"]
    D3_sub --> D3_2["다낭성난소증후군에<br>부합"]
    D3_sub --> D3_3["빠른 증상 시작 or<br>매우 높은 androgen"]

    D3_1 --> D3_1_sub["late-onset<br>congenital adrenal<br>hyperplasia 고려"]
    D3_2 --> D3_2_sub["대사증후군 선별 검사;<br>진단에 따른 치료"]
    D3_3 --> D3_3_sub["adrenal & ovarian 영상<br>검사 고려(R/O 종양)"]

    D4 --> D4_sub["소퇴성 출혈 호르몬 유도<br>고려, hysteroscopy<br>(자궁내 유착 평가)"]

    %% 하단 주석
    FOOTNOTE["*명확한 진단을 위하여 필요시 1개월 후에 반복할 수 있음"]

    %% 색상 및 스타일 지정
    classDef purple fill:#EAE8F8,stroke:#B0A3E0,color:#333
    classDef green fill:#E2F0D9,stroke:#A9D08E,color:#333
    classDef blue fill:#DDEBF7,stroke:#9BC2E6,color:#333
    classDef yellow fill:#FFF2CC,stroke:#FFE699,color:#333
    classDef pink fill:#FCE4D6,stroke:#F4B08A,color:#333
    classDef note fill:none,stroke:none,color:#555,font-style:italic

    class A purple
    class B,E_sub,D2_sub,D3_sub,D3_2_sub,D3_3_sub,D4_sub green
    class C blue
    class D,E,D1,D2,D3,D4,D3_1,D3_2,D3_3 yellow
    class D1_sub,D3_1_sub pink
    class FOOTNOTE note
```

2차성 무월경의 진단\
Ref. Amenorrhea: A Systematic Approach to Diagnosis and Management. AFP. 2019;100(1). Fig 2.

***

## Management

### 치료 방침

* 원인 질환 치료(예: 갑상선 질환, hyperprolactinemia)
* 영양, 적정 체중 관리 : 비만인 경우 감량, 체중이 너무 적은 경우 증량
* 심한 운동/활동을 하는 경우 운동량을 줄이고(25\~50% 감량) 칼로리 섭취를 늘림
* 스트레스 관리
* 호르몬제 치료(예: hypogonadism, ovarian insufficiency)
* 저용량 corticosteroid(예: adult onset congenital adrenal hyperplasia)
* 수술적 치료(예: Mullerian agenesis, malignancy)
* 합병증으로서의 골다공증 평가 및 관리 (☞ p.804)

### 호르몬제 (☞ [피임](131_-contraception.md))

* estrogen(경구 피임제) : 불규칙한 주기에 대하여 투여
* medroxyprogesterone acetate(MPA) : 10 ㎎/d ×10d \[프로베라]
  * hypothalamic–pituitary–gonadal axis가 유효하면 마지막 투여 7일 내 소퇴성 출혈 발생
* 복합 경구 피임제 : estrogen 50 ㎍ 또는 conjugated estrogen 0.625 ㎎ ×25d with progesterone 최소 10d [야스민](../%EB%B9%84%EB%B3%B4%ED%97%98/)
  * uterus and lower genital tract이 정상이고 HPG axis에 이상이 있으면 소퇴성 출혈 발생
* 호르몬제 금기 및 부작용에 대하여 유의
* 호르몬 보충 요법 적용 시 6개월 후에 중단하고 자발적 월경 재개를 평가

### **질병코드**&#x20;

N91.0 원발성 무월경

N91.1 이차성 무월경
