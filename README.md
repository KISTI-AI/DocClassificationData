
# 논문, 보고서, 특허 과학기술표준분류 데이터셋
 본 데이터셋은 논문, 보고서, 특허의 제목과 요약문을 과학기술표준분류(2023년 버전)의 중분류와 소분류로 분류한 데이터셋이다.

## 데이터 포맷(TXT)
|유형|설명|
|--|--|
|research_id |NTIS 과제번호|
|code|2023년도 과학기술표준분류코드|
|similarity|해당 코드에 대한 ChatGPT의 설명문 임베딩과 제목+요약문 임베딩간에 코사인유사도|
|type|논문, 보고서, 특허 유형|
|title_abstract|각 유형의 제목과 요약문을 취합한 입력문장|

## 데이터 통계
- 중분류 데이터셋 : 961,851건
- 소분류 데이터셋 : 314,234건
- 레이블 개수 : 중분류 185개, 소분류 1,254개

## 예제
research_id code similarity type title_abstract
1415167736 EB0108 0.8298083304216014 patent 전해정련을 이용한 고순도 네오디뮴 회수방법 본 발명은 불화리튬 (lif) 및 불화칼슘 (caf2)을 함유하는 용융염을 이용한 전해정련을 통하여, 네오디뮴-디스프로슘 합금으로부터 고순도 네오디뮴의 회수 방법을 제공한다. 본 발명에 따르면, 희토류 자석으로부터 추출된 네오디뮴-디스프로슘 합금에서 네오디뮴(nd)을 높은 추출 효율 및 단순하고 경제적인 추출 공정으로 회수할 수 있고, 건식 공정이어서 환경 문제에 대한 부담이 적은 효과가 있다.
1395046214 LB0305 0.7849073675453806 paper 익힌 숙잠의 알콜성 질환 예방 효과 우리나라는 국민 1인당 연간 음주량이 세계 190여개 국가 중 15위권 안에 들 정도로 술을 많이 마시는 국가로, 과도한 음주로 인한 지방간, 간경화, 위염, 숙취 등 빈번한 알콜성 질환의 발생으로 개인적, 사회적 비용이 과도하게 지불되고 있는 상황이다. 익힌 숙잠 생산기술은 세계 최초로 개발된 기술로서 지금까지는 섭취가 불가능했던 5령 3일 이후부터 숙잠까지의 누에, 즉 숙잠을 섭취할 수 있도록 분말로 만드는 기술이다. 이 기술로 제작된 익힌 숙잠 분말을 사용하여 알콜성 지방간, 간경화, 위염 및 숙취 등 알콜성 질환에 대한 예방효과를 시험하였다. 그 결과, 익힌 숙잠의 지속적인 섭취는 알콜 투여 후, 혈중 알콜 농도 및 그 대사산물인 아테트알데히드를 현저하게 감소시켰을 뿐만 아니라, 알콜에 의해서 유도된 지방간, 간섬유증 및 위염을 현저하게 예방하는 효과를 나타냈다. 따라서 익힌 숙잠을 지속적으로 섭취한다면 국민건강증진과 보건의료비용의 감소 및 양잠산업발전 등 1석3조의 효과를 기대할 수 있을 것이다.
1711078644 EI0606 0.8081579607040635 paper 구조광 기술을 이용한 레이저 스펙클 기반의 변형률 측정 센서 접촉식 기반 변형률 측정 센서는 접촉 방식의 고질적인 문제로 부착 위치에 따라 변형률 측정값의 오차를 동반하며, 센서 탈부착 시 파손의 위험 또한 가져온다. 이를 극복하기 위하여, 본 연구는 시편의 변형에 매우 민감한 레이저 스펙클 영상(laser speckle imaging)을 이용한 비접촉식 센서를 구현하였다. 기존의 보고된 스펙클 기반의 센서들은 주변광(ambient light)에 취약하여 현장 적용에 어려움이 따른다. 본 연구에서는 주변광 환경에서도 고대조 및 고민감도 측정이 가능하게 하고자 구조광(structured illumination) 기술을 적용하였다. 또한, 취득한 레이저 스펙클 영상에 대하여 2차원 상관관계 분석을 통해 정량적인 변형률 값을 산출하였다. 알루미늄 시편의 인장 실험을 실시하여 변형률 게이지(strain gauge)와 비교 분석하였으며, 0.99의 높은 상관관계를 확인하였다. 본 센서는 정밀한 동시에 주변광에도 강건한 특성은 실제 철로 유지관리와 같은 현장에 응용될 수 있음을 시사한다.
1415155091 ED0210 0.8294236332199664 patent 상압소결 실리콘 카바이드 웨이퍼 캐리어 및 결합구조와 그 결합방법 본 발명은 상압소결 실리콘 카바이드 웨이퍼 캐리어 및 결합구조와 그 결합방법에 관한 것으로, 더욱 자세하게는 다수의 지지바(30)와 상기 지지바(30)의 양측에 각각 결합되는 상, 하부플레이트(10, 20)로 구성되되, 상기 지지바(30)와 상, 하부플레이트(10, 20)를 결합 시, 1200˚c 온도에서도 사용이 가능하고, 내부식성 및 고온 강도가 강하며, 반도체 공정 사용 수명이 rb sic반응소결 실리콘 카바이드에 비해 더 길고, cvd sic coating 시 흡착력 우수와 사용 중 파손 시 수리 가능한 결합구조 및 그 방법을 제공함으로써, 경제적 효율성과 편리성을 동시에 부여할 수 있는 유용한 발명인 것이다.
1395048567 LB0305 0.8027775242722348 paper 오디생산용 뽕나무 시기별 누에사육가능성 분석 전라북도 부안군 비닐하우스와 노지에서 재배되고 있는 오디 생산용 뽕나무(과상 2호)를 대상으로 누에사육용 뽕나무 청일뽕을 대조구로 하여 각각 뽕잎을 활용하여 시기별로 누에사육가능성을 분석하고자 하였다. 누에사육시기는 수확전과 수확기, 수확후로 구분하여 각각 5월 1일과, 5월 20일, 6월 10일에 소잠을 하고 5령 3일까지 사육을 실시하면서 각 시기별 누에 발육특성 및 뽕잎생산량을 비교하였다. 발육특성은 령기별 누에 발육기간 및 5령 3일 누에 무게, 감잠비율 등을 조사하였다. 시기별 누에 발육기간은 5령 3일까지 20일~22일 정도가 소요되었고, 수확전과 수확후에 비해 수확기에서 약간 빠른 경향이나, 큰 차이는 없었다. 각 뽕잎별 5령 3일 무게로 볼 때 수확전에는 청일뽕과 노지 뽕잎에 비하여 하우스뽕잎에서 발육이 부진하였고, 수확기에는 하우스, 노지 뽕잎 모두 청일뽕과 비슷하였지만, 수확후에는 노지 뽕잎에서 발육이 가장 좋았다. 감잠비율은 청일뽕에 비하여 과상 2호에서 높은 경향이고, 하우스 뽕잎에서 감잠비율이 가장 높았다. 또한, 소잠시기가 늦을수록 감잠비율이 많아지는 경향이었다. 시기별 과상 2호 뽕잎량은 수확전에는 청일뽕에 비하여 하우스에서 뽕잎량이 가장 많았고, 노지는 생육이 느려 상대적으로 부족하였으나, 청일뽕에 비하여 주당 뽕잎무게는 많은 경향이었다. 수확기와 수확후에는 노지와 하우스 뽕잎량은 비슷하였고, 청일뽕이 가장 적었다. 따라서, 수확기에도 누에사육이 가능하나, 수확작업 때문에 작업능률이 떨어질 것으로 판단되고, 수확전과 수확후에는 하우스, 노지 모두 누에 사육이 가능할 것으로 판단되며, 다만, 노지 뽕잎은 수확전에 뽕잎량이 부족할 것으로 보여 많은 량을 사육하지는 못할 것으로 판단된다.
1711060009 LC0301 0.8283563397995648 patent blt 저해 활성을 갖는 화합물을 유효성분으로 포함하는 아토피 예방 또는 치료용 약학적 조성물 본 발명은 blt2 (leukotriene b4 receptor 2) 억제 활성을 나타내는 화합물, 이의 이성질체 또는 이의 약학적 허용가능한 염을 유효성분으로 포함하는, 아토피(atopic dermatitis)의 예방 또는 치료용 약학적 조성물에 관한 것이다. 본 발명자들은 btl2 억제 활성을 나타내는 화합물의 우수한 주화성 억제 효과 및 아토피 치료 효과 등을 실험적으로 확인하였는바, 본 발명의 화합물은 아토피를 치료하기 위한 약학적 조성물로 유용하게 사용될 수 있을 것으로 기대된다.
1711048155 NC0308 0.8174342544699759 patent 퀴놀린 4-온 유도체 또는 이의 약학적으로 허용 가능한 염을 유효성분으로 포함하는 폐렴의 예방 또는 치료용 약학적 조성물 본 발명은 퀴놀린 4-온 유도체, 이의 약학적으로 허용 가능한 염, 또는 이를 유효성분으로 포함하는 폐렴의 예방 또는 치료용 약학적 조성물에 관한 것이다. 본 발명에 따른 퀴놀린 4-온 유도체는 우수한 항균활성을 가질 뿐만 아니라, 종래 일반적으로 사용되고 있는 항균제와는 달리 약물 내성을 갖고 있는 폐렴균에 대해서도 항균 활성이 뛰어나므로 이들 폐렴균에 의해서 발병되는 폐렴의 예방 또는 치료용 약학적 조성물로써 유용하게 사용될 수 있다.
1345274028 EC0103 0.6762329957051496 paper gelatin-based extracellular matrix cryogels for cartilage tissue engineering in this study, gelatin-based cryogels were fabricated by mixing methacrylated gelatin (gelma) with methacrylated hyaluronic acid (meha) or methacrylated chondroitin sulfate (mecs) for cartilage tissue engineering. in vitro revealed that mecs incorporated gelatin-based cryogel (g-mecs) showed significant cartilaginous tissue stimulation. furthermore, the cell-laden gelatin-based ecm cryogels were implanted into mouse subcutaneous tissue for 6 weeks and displayed uniform distribution of cells with normal phenotype maintenance. finally, when these cryogels were implanted into osteochondral defect of new zealand white rabbit, full integration with host tissue and increased cellularity were observed with g-mecs cryogel. (c) 2016 the korean society of industrial and engineering chemistry. published by elsevier b.v. all rights reserved.
1345277451 LC0110 0.7889292570676942 patent 질병 예측 시스템 본 발명의 실시 예에 따른 질병 예측 시스템은 사용자의 질병 예측에 요구되는 유전적, 환경적, 생활습관적 개인정보를 질병 예측 서버로 제공하는 사용자 기기, 상기 사용자 기기로부터 제공받은 개인정보를 통계적 방법과 기계학습법을 이용한 질병 예측 모델에 적용하여 사용자의 질병에 대한 발병 위험을 수치 데이터로 산출하는 질병 예측 서버 및 해당 질병과 관련된 임상 및 유전상담 정보를 제공하는 공공 db를 포함하는 것을 특징으로 한다.
1711053191 EH0104 0.8029917995724812 patent 복합 금속 입자 제조장치 및 제조방법 본 발명은 복합 금속 입자 제조장치 및 제조방법에 관한 것으로, 본 발명의 일 측면에 따르면, 화염 영역을 형성하기 위한 화염 반응기; 복합 금속 입자를 생성하기 위하여, 금속 입자 및 전구체 용액을 각각 화염 영역 측으로 공급하기 위한 하나 이상의 공급부; 및 화염 영역 측으로 초음파를 분사하도록 마련된 초음파 발생기를 포함하는 복합 금속 입자 제조장치가 제공된다.
1415168124 EF0601 0.8105266813447929 patent 에너지 스마트팜 센싱 데이터 오류 식별방법 본 발명은 센서 네트워크 환경에서의 오류 데이터 식별방법에 관한 것으로, 구체적으로는 센서들을 통해 측정된 전력정보들을 수집하는 센서노드 및 상기 센서노드에서 수집한 데이터를 저장하는 센서로거를 포함하는 센서 네트워크 환경에서 각 센서, 상기 센서노드 또는 상기 센서로거에서 발생할 수 있는 데이터의 오류를 식별하는 것으로, 특히, 에너지 스마트팜에서 사용가능한 센서 네트워크 환경에서의 오류 데이터 식별방법에 관한 것이다.
1345278418 EA0210 0.7022551980243033 paper optimal number of components in a load-sharing system for maximizing reliability a k-out-of-n:g load sharing system is a cluster of n components designed to withstand a certain amount of load in field operation, working only if no fewer than k components work. previous research on a load sharing system has focused on predicting the time-independent reliability from the stress-strength model or estimating the unknown parameters of the time-dependent reliability for a given load sharing rule. differently, in this paper, we consider the problem of determining the optimal n to maximize the reliability of both n-out-of-n:g and (n-1)-out-of-n:g load sharing systems. since the load of each component decreases in n, the proportional hazard model is employed to relate the component failure rate with the load, assuming that the components, which have exponential distributions for given loads, are independent of each other. we then derive a sufficient condition under which a smaller number of components each withstanding a high load is preferred to a larger number of components each withstanding a small load. a numerical example is given for the rocket propulsion system to illustrate the result.
1545016652 LB1801 0.7184173006918623 paper chloroplast dna-derived markers for the authentication of oriental medicinal rubus species and mistaken identity of bokbunja in the local markets of korea the traditional oriental medicine bokbunja, prepared from immature berries of rubus coreanus is used as an anti-oxidant,diuretic, and cure for impotence. the bokbunja wine made from fermented fruits of bokbunja has been used as a functionalfood as well. however, the usage of bokbunja has been problematic over the years due to the abundance of mistakenlyidentified berries such as rubus chingii, rubus crataegifolius, and rubus occidentalis. thus, here we developed a methodfor the molecular differentiation of rubus species as well as the authentication bokbunja from other rubus species. wescreened several sequences from the chloroplast dna of these species and found that the rpl16 region was polymorphicfor r. coreanus and r. occidentalis, while the trng–trns intergenic spacer region was polymorphic for r. chingii and r.crataegifolius. species-specific primers were designed and a multiplex pcr was performed by combining the markers atthe rpl16 and trng–trns regions. amplicons of 686 bp for r. coreanus and 478 bp for r. occidentalis were produced by theprimers 5′ rcor or 5′ rocci, respectively, with 3′ rpl16; whereas, amplicons of 389 bp for rubus crataegifolius and 180 bpfor r. chingii were produced by 5′ rcra or 5′ trng–trns, respectively, and 3′ rcra/rchi. the deduced molecular markers wereutilized to authenticate the bokbunja products and demonstrated that the majority of bokbunja samples from the marketswere adulterant berries. hence, our results indicate that the produced molecular markers can serve as an effective tool toauthenticate bokbunja.
1711071232 LC0603 0.8006337804347129 paper cost comparison of androgen deprivation therapy and radical prostatectomy for prostate cancer purposes: 본 연구는 전립선암 환자의 의료비 지출을 평가하기 위해 남성호르몬 박탈 치료와 근치적 전립선적출술의 비용을 비교하였다. methods: 본 연구는 스마트 전립선암 데이터베이스(smart prostate cancer database)의 전립선암 환자 357명의 데이터와 청구데이터베이스에서 의료비 관련 데이터를 도출하였다. 근치적 전립선적출술과 남성호르몬 박탈 치료간 비교를 위해 독립표본 t검정을 실시하였다. 또한 남성호르몬 박탈 치료와 근치적 전립선적출술에 영향을 미치는 요인을 검증하기 위해 다중회귀 분석을 실시하였다. findings: 치료 후 1년까지 남성호르몬 박탈치료가 근치적 전립선적출술 보다 비용이 낮은 것으로 나타났으며, 치료 후 4년까지 낮게 유지되었다. 그러나 4년이 지나면 남성호르몬 박탈 치료의 누적의료비가 근치적 전립선적출술보다 더 유의미하게 높게 나타났다. 환자의 병기가 높거나 나이가 많은 경우 근치적 전립선적출술보다 남성호르몬 박탈 치료를 할 확률이 더 높았다. practical implications: 본 연구는 조기 암 발견이 환자 뿐 아니라 국민건강보험공단의 의료비를 줄일 수 있다는 것을 보여 준다. 또한 의료비를 정확히 평가하기 위해서는 오랜 기간의 정보를 평가해야 하며, 이를 기반으로 평가 및 예측이 필요함을 증명하였다.
1711047293 EC0103 0.6946216096187761 paper effects of vibrations in marine environments on performance of molten-carbonate fuel cells owing to the strengthening of environmental regulations, highly efficient and environmentally sustainable power supply systems have attracted significant attention as auxiliary power units (apus) for marine applications. among several candidates, molten carbonate fuel cells (mcfcs) is of particularly interest because it provides high efficiency with essentially no greenhouse gas emissions of nox and sox. in this study, the effects of vibrations caused by sea-waves and swells on the operation of mcfcs on marine ships are investigated. an mcfc single cell with a unit area of 100 cm2 was tested in a vibration environment at an operating temperature of 620 oc. at a low sealing pressure (0.1 mpa), the performance of the cell decreased owing to increased mass-transfer resistance. electrochemical impedance spectroscopy revealed that using oxygen and co2 as the cathode reactants mitigates the degradation by the vibration induced mass-transfer resistance. in addition, the mcfc single cell is operated under various vibration conditions, including the resonance frequency (13 and 29 hz). it was found that the vibration environment does not affect the performance of mcfcs under normal operating conditions.
1415146859 EC0304 0.7908056708780745 paper concentration-mediated multicolor fluorescence polymer carbon dots abstractpolymer dots (pds) showing concentrationmediated multicolor fluorescence were first prepared from sulfuric acidtreated dehydration of pluronic f127 in a single step. pluronicbased pds (ppds) showed high dispersion stability in solvent media and exhibited a fluorescence emission that was widely tunable from red to blue by adjusting both the excitation wavelengths and the ppd concentration in an aqueous solution. this unique fluorescence behavior of ppds might be a result of crosstalk in the fluorophores of the poly(propylene glycol)rich core inside the ppd through either energy transfer or charge transfer. reconstruction of the surface energy traps of the ppds mediated through aggregation may lead to a new generation of carbonbased nanomaterials possessing a fluorescence emission and tunable by adjusting the concentration. these structures may be useful in the design of multifunctional carbon nanomaterials with tunable emission properties according to a variety of internal or external stimuli. copyright 2015 john wiley sons, ltd.
![docimage1](https://github.com/user-attachments/assets/639ddb04-43cc-4dff-8fa3-83c33b7e86be)

## 데이터 구축방법
![docimage2](https://github.com/user-attachments/assets/65325cd4-1d4c-4ce6-a6f0-1dab3c21d2a2)

##  데이터 다운로드
http://doi.org/10.23057/70

## 라이선스
비영리 이용, 출처 표기, 재배포 금지
