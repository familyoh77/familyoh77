# 목쉼 Hoarseness

* 목소리의 떨림, 약해짐, 긴장, 음조 변화, 성량 부족 등의 현상이 발생한 voice quality의 변화

## 원인

| 급성     | 원인                        |
| ------ | ------------------------- |
| 급성 후두염 | 바이러스, 세균                  |
| 성대 출혈  | 목소리 과사용, 잘못된 사용           |
| 후비루    | 부비동염, 알레르기                |
| 위식도역류  | 위산                        |
| 경부 외상  | 외상                        |
| 갑상선 질환 | 갑상선저하증                    |
| 정신적 문제 | 신체화장애, Hysterical aphonia |

| 만성         | 원인                                   |
| ---------- | ------------------------------------ |
| 만성 후두염     | 바이러스, 세균, 흡연                         |
| 악성 종양      | 편평상피암, 갑상선암                          |
| 성대 결절      | 목소리 과사용/잘못된 사용                       |
| 성대 폴립      | 목소리 과사용/잘못된 사용, 흡연, 알레르기             |
| Papillomas | Recurrent respiratory papillomatosis |
| 성대 마비      | 암, 외상, 뇌경색, 퇴행성 질환                   |

#### 약물

* coumadin, thrombolytics, PDE5i : vocal fold hematoma
* bisphosphonate : 화학적 후두염
* ACEI : 기침
* 항히스타민제, 항콜린제, 이뇨제 : 점막 건조
* 항정신병제 : laryngeal dystonia
* 흡입 steroid : 용량 의존 점막 자극; 진균성 후두염

### Red Flags!

* 6주 이상 지속 (기간 중 무증상 상태 없음)
* 객혈
* 호흡 곤란, 삼킴곤란
* 목의 종괴
* 편측 이통
* 흡연, 알코올 남용
* 외상, 수술, 경부 침습성 검사, 방사선 치료 후 발생
* 설명할 수 없는 체중 감소 또는 쇠약 R

## 진단

### 검사

* 후두경 검사 : 음성 치료 전에 시행
* CT/MRI 검사 : 후두 관찰 후 고려
* \[국가암정보센터] 6주 이상 지속되는 원인 불명의 쉰 목소리에 대하여 후두암 검사 권고
* \[AAO-HNSF] 목쉼 증상 3개월 이상 지속되거나 심각한 기저 질환 의심 시 후두경 검사 권고

> ✽URI 후 1주간 목쉼이 지속될 수 있음 ✽dysplasia 고위험군(예: 흡연, heavy alcohol use, 객혈)은 ＞2주 목쉼이 지속되는 경우 후두경 검사를 권하는 견해가 있음



***

```mermaid
graph TD
    Title[<b><2주 목쉼</b>] 
    style Title fill:none,stroke:none,font-size:20px

    Start([최근 목소리 남용 또는<br/>URI or Allergy 증상 이력?])
    
    Start -- yes --> A[Voice rest,<br/>대중 치료]
    Start -- no --> B([최근 위식도 or<br/>인후두역류 증상?])
    
    A --> A1([2주 내 호전?])
    A1 -- yes --> A2[대중 치료 유지,<br/>재발 시 Laryngoscopy]
    A1 -- no --> A3[Laryngoscopy]
    
    B -- yes --> C[고용량 PPI<br/>단기 치료]
    B -- no --> D[2주간 지지요법 &<br/>vocal hygiene; 호전 안 되면<br/>Laryngoscopy 고려]
    
    C --> C1([4주 내 호전?])
    C1 -- yes --> C2[PPI 치료 유지;<br/>재발 시 Laryngoscopy]
    C1 -- no --> C3[Laryngoscopy]

    %% 스타일 설정
    classDef yellow fill:#FFF9C4,stroke:#FBC02D;
    classDef blue fill:#E3F2FD,stroke:#90CAF9;
    classDef green fill:#E8F5E9,stroke:#A5D6A7;
    
    class Start,B,A1,C1 yellow;
    class A,A2,C,C2,D blue;
    class A3,C3 green;
```

```mermaid
graph TD
    Title[<b>>2주 지속되는 목쉼</b>]
    style Title fill:none,stroke:none,font-size:20px

    Start([dysplasia or 암 증상 또는 위험 인자<br/>흡연, 과음, 장기간의 GERD, 객혈?])
    
    Start -- yes --> L1[Laryngoscopy]
    Start -- no --> Q2([최근 흡입 steroid 사용?])
    
    Q2 -- yes --> A[fluticasone 회피;<br/>가능하다면 흡입<br/>steroid 중단 or 감량]
    Q2 -- no --> B([목쉼을 유발하는<br/>전신질환 예: 파킨슨병,<br/>갑상선저하증?])
    
    A --> A1([4주 내 호전?])
    A1 -- yes --> A2[흡입 steroid<br/>유효 최소량 사용;<br/>재발 시 Laryngoscopy]
    A1 -- no --> L2[Laryngoscopy]
    
    B -- yes --> C[기저 질환 치료]
    B -- no --> L3[Laryngoscopy]
    
    C --> C1([4주 내 호전?])
    C1 -- yes --> C2[기저질환치료 유지,<br/>재발 시 Laryngoscopy]
    C1 -- no --> L4[Laryngoscopy]

    %% 스타일 설정
    classDef yellow fill:#FFF9C4,stroke:#FBC02D;
    classDef blue fill:#E3F2FD,stroke:#90CAF9;
    classDef green fill:#E8F5E9,stroke:#A5D6A7;
    
    class Start,Q2,B,A1,C1 yellow;
    class A,A2,C,C2 blue;
    class L1,L2,L3,L4 green;
```



***

## Management

### 치료 방침

* 원인 치료
* 음성 치료(발성법, 목 관리법)
* 약물
* 수술

## 비-약물 치료

* 가습, 수분 섭취 늘림
* 이완 훈련
* 오염된 공기 회피 : 흡연, 먼지, 호흡기 자극 물질
* 냉/난방 기기(특히 선풍기, 온풍기) 회피
* 헛기침 또는 throat clearing 자제
* 고성, 소리 지름, 속삭임, 크거나 센 웃음 자제

> ✽속삭임은 성대 긴장을 높이기 때문에 쉰 목소리 회복에 도움이 되지 않음

* 후두 분비물 증가 및 성대 건조 유발 음식 회피 : 설탕, 커피, 고지방식, 유제품, 탄산음료
* GERD 유발 음식 회피 : 과식, 카페인, 음주, 신 음식, 탄산음료

## 약물 치료

* 명확한 적응증이 아닌 경우의 PPI, 경구 steroid, 항생제의 경험적 사용은 피함
*   steroid

    •저용량 흡입제 budesonide \[풀미코트] (☞ p.346) (✽fluticasone은 자극 및 후두염의 원인이 되므로 피함)

    •바로 목소리를 내야 하는 직업인에 대하여 경구/IM steroid를 제한적으로 고려
*   고용량 PPI : 역류 질환에 대한 시험적 치료; 다른 원인을 배제한 후 full-strength로 1일 2회 최소 3개월 투여.

    예) omeprazole 40 ㎎ bid (☞ p.295, p.406)
* 근이완제 : 평활근 이완 : baclofen 5 ㎎ tid \[바크론]
* 보톡스 주사 : 경련성 발성장애가 있는 경우 고려

> ✽쉰 목소리 치료를 위한 일상적인 항생제나 steroid 처방은 피함

> **질병코드** R49.0 목쉼

처방례

처방례 1.\
풀미코트 터부헬러 1 puff bid\
바크론 5 ㎎/T 3T #3\
처방례 2. 위식도 역류 관련\
오엠피 40 ㎎/T 1T bid (보험주의)\
가나칸 50 ㎎/T 3T #3\
처방례 3. 알레르기비염/구강 호흡 관련\
리노에바스텔 1C qd 저녁
