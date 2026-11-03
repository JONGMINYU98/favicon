# 식품안전정보레터 메일 그림

농심 식품안전팀 '데일리 식품안전 정보레터' 메일에 들어가는 그림을 두는 곳입니다.
메일 본문에는 그림 대신 이 주소가 들어가고, 받는 사람의 메일 앱이 여기서 그림을 불러옵니다.

메일에 넣는 주소는 jsDelivr를 거칩니다(캐시와 속도 때문):
`https://cdn.jsdelivr.net/gh/JONGMINYU98/favicon@main/letter/<파일>`

- 그림을 바꾸거나 새로 넣으면 jsDelivr 캐시 때문에 실제 반영까지 최대 12시간이 걸릴 수 있습니다.
- 이미 보낸 메일도 같은 주소를 쓰므로 **파일 이름은 바꾸거나 지우지 말고**, 번호는 뒤에만 덧붙이세요.

## 배너 (680px 폭, 2배 해상도)

| 파일 | 내용 |
|---|---|
| `banner_ivoryplus.gif`, `banner_midnightplus.gif` | 고급형 움직이는 배너(아이보리 / 미드나잇) |
| `banner_ivory.png`, `banner_midnight.png`, `banner_mono.png` | 고급형 정지 배너 |
| `banner_photo_spice.jpg`, `_grain`, `_lab`, `_veg` | 사진형 배너 |
| `banner_news.png` | 신문형 제호 |

## 사진 풀 `pool/`, 표지 `cover/`

맨 위 '오늘 꼭 볼 소식'(대표기사)에 원문 사진이 없을 때 쓰는 참고 사진입니다. 26개 분류, 139장입니다.

- `pool/<분류>_<번호>.jpg`: 1232×560, 메일에서 616×280으로 보입니다.
- `pool/<분류>_<번호>_s.jpg`: 240×180, 편집화면의 사진 고르기 칸에 씁니다.
- `cover/<분류>_<번호>.jpg`: 1360×600, 사진 표지형 양식의 머리 그림입니다(사진 아래쪽을 남색으로 덮고 제목을 새긴 것).

| 분류 키 | 이름 | 장수 |
|---|---|---|
| microbe | 미생물 | 7 |
| lab | 검사·분석 | 8 |
| chili | 향신료 | 7 |
| nuts | 견과·알레르기 | 7 |
| seafood | 수산물 | 6 |
| meat | 축산물 | 6 |
| dairy | 유제품 | 6 |
| eggs | 알 | 6 |
| packaging | 포장·용기 | 6 |
| label | 표시 | 5 |
| grain | 곡류 | 7 |
| pesticide | 농약 | 5 |
| law | 법령 | 5 |
| import | 수입·통관 | 6 |
| veg | 채소 | 6 |
| fruit | 과일 | 6 |
| supplement | 건강기능식품 | 5 |
| noodle | 면류 | 6 |
| snack | 과자 | 5 |
| sauce | 소스·장류 | 4 |
| beverage | 음료 | 4 |
| coffee | 커피 | 3 |
| tea | 차 | 3 |
| honey | 꿀·당류 | 4 |
| oil | 식용유 | 3 |
| seaweed | 해조류 | 3 |

## 기존 레터 그림 백업 `legacy/`

사내 이미지 서버(`image.nongshim.com/mail/daily/image/`)에 있는 원래 레터 배너 조각 4개와 기관 로고 5개를 2026-11-03에 복사해 둔 것입니다.
메일은 아직 사내 서버 주소를 씁니다. 사내 서버 파일이 바뀌거나 사라지면 대시보드 Code.gs의 `IMG_BASE`를 이 폴더로 바꾸면 됩니다.

## 사진 출처

모든 사진은 [Pexels 무료 라이선스](https://www.pexels.com/license/) 사진입니다. 상업적으로 쓸 수 있고, 출처를 표기할 의무는 없습니다.
메일 크기에 맞게 잘라서 올렸습니다.

배너 사진: grain [7421301](https://www.pexels.com/photo/7421301/) · lab [4033148](https://www.pexels.com/photo/4033148/) · spice [5741508](https://www.pexels.com/photo/5741508/) · veg [1458694](https://www.pexels.com/photo/1458694/)

| 파일 | 원본 |
|---|---|
| microbe_1 | [4031501](https://www.pexels.com/photo/4031501/) |
| microbe_2 | [4031366](https://www.pexels.com/photo/4031366/) |
| microbe_3 | [4033022](https://www.pexels.com/photo/4033022/) |
| microbe_4 | [6203349](https://www.pexels.com/photo/6203349/) |
| microbe_5 | [8940346](https://www.pexels.com/photo/8940346/) |
| microbe_6 | [10419527](https://www.pexels.com/photo/10419527/) |
| microbe_7 | [8940354](https://www.pexels.com/photo/8940354/) |
| lab_1 | [4033148](https://www.pexels.com/photo/4033148/) |
| lab_2 | [8533087](https://www.pexels.com/photo/8533087/) |
| lab_3 | [9243563](https://www.pexels.com/photo/9243563/) |
| lab_4 | [8770717](https://www.pexels.com/photo/8770717/) |
| lab_5 | [4032274](https://www.pexels.com/photo/4032274/) |
| lab_6 | [8325939](https://www.pexels.com/photo/8325939/) |
| lab_7 | [3912512](https://www.pexels.com/photo/3912512/) |
| lab_8 | [18689301](https://www.pexels.com/photo/18689301/) |
| chili_1 | [221140](https://www.pexels.com/photo/221140/) |
| chili_2 | [7956502](https://www.pexels.com/photo/7956502/) |
| chili_3 | [7208238](https://www.pexels.com/photo/7208238/) |
| chili_4 | [33440713](https://www.pexels.com/photo/33440713/) |
| chili_5 | [6220710](https://www.pexels.com/photo/6220710/) |
| chili_6 | [877220](https://www.pexels.com/photo/877220/) |
| chili_7 | [2632292](https://www.pexels.com/photo/2632292/) |
| nuts_1 | [135755](https://www.pexels.com/photo/135755/) |
| nuts_2 | [5472169](https://www.pexels.com/photo/5472169/) |
| nuts_3 | [10111993](https://www.pexels.com/photo/10111993/) |
| nuts_4 | [34142354](https://www.pexels.com/photo/34142354/) |
| nuts_5 | [86649](https://www.pexels.com/photo/86649/) |
| nuts_6 | [9615878](https://www.pexels.com/photo/9615878/) |
| nuts_7 | [23384625](https://www.pexels.com/photo/23384625/) |
| seafood_1 | [2714384](https://www.pexels.com/photo/2714384/) |
| seafood_2 | [8352344](https://www.pexels.com/photo/8352344/) |
| seafood_3 | [12955692](https://www.pexels.com/photo/12955692/) |
| seafood_4 | [96379](https://www.pexels.com/photo/96379/) |
| seafood_5 | [8351650](https://www.pexels.com/photo/8351650/) |
| seafood_6 | [38222958](https://www.pexels.com/photo/38222958/) |
| meat_1 | [36319690](https://www.pexels.com/photo/36319690/) |
| meat_2 | [33157191](https://www.pexels.com/photo/33157191/) |
| meat_3 | [31916996](https://www.pexels.com/photo/31916996/) |
| meat_4 | [27743370](https://www.pexels.com/photo/27743370/) |
| meat_5 | [28881694](https://www.pexels.com/photo/28881694/) |
| meat_6 | [10647859](https://www.pexels.com/photo/10647859/) |
| dairy_1 | [4910809](https://www.pexels.com/photo/4910809/) |
| dairy_2 | [248412](https://www.pexels.com/photo/248412/) |
| dairy_3 | [4324359](https://www.pexels.com/photo/4324359/) |
| dairy_4 | [2887112](https://www.pexels.com/photo/2887112/) |
| dairy_5 | [5947086](https://www.pexels.com/photo/5947086/) |
| dairy_6 | [1435706](https://www.pexels.com/photo/1435706/) |
| eggs_1 | [4184073](https://www.pexels.com/photo/4184073/) |
| eggs_2 | [600615](https://www.pexels.com/photo/600615/) |
| eggs_3 | [33653802](https://www.pexels.com/photo/33653802/) |
| eggs_4 | [2889375](https://www.pexels.com/photo/2889375/) |
| eggs_5 | [4110225](https://www.pexels.com/photo/4110225/) |
| eggs_6 | [6845644](https://www.pexels.com/photo/6845644/) |
| packaging_1 | [5794767](https://www.pexels.com/photo/5794767/) |
| packaging_2 | [4033160](https://www.pexels.com/photo/4033160/) |
| packaging_3 | [5719961](https://www.pexels.com/photo/5719961/) |
| packaging_4 | [30893288](https://www.pexels.com/photo/30893288/) |
| packaging_5 | [5719860](https://www.pexels.com/photo/5719860/) |
| packaging_6 | [33930755](https://www.pexels.com/photo/33930755/) |
| label_1 | [28907758](https://www.pexels.com/photo/28907758/) |
| label_2 | [6097890](https://www.pexels.com/photo/6097890/) |
| label_3 | [3737645](https://www.pexels.com/photo/3737645/) |
| label_4 | [7418385](https://www.pexels.com/photo/7418385/) |
| label_5 | [6097883](https://www.pexels.com/photo/6097883/) |
| grain_1 | [7421301](https://www.pexels.com/photo/7421301/) |
| grain_2 | [7891849](https://www.pexels.com/photo/7891849/) |
| grain_3 | [36346840](https://www.pexels.com/photo/36346840/) |
| grain_4 | [7421207](https://www.pexels.com/photo/7421207/) |
| grain_5 | [226615](https://www.pexels.com/photo/226615/) |
| grain_6 | [1423597](https://www.pexels.com/photo/1423597/) |
| grain_7 | [11789293](https://www.pexels.com/photo/11789293/) |
| pesticide_1 | [39564718](https://www.pexels.com/photo/39564718/) |
| pesticide_2 | [4975345](https://www.pexels.com/photo/4975345/) |
| pesticide_3 | [31834386](https://www.pexels.com/photo/31834386/) |
| pesticide_4 | [23247806](https://www.pexels.com/photo/23247806/) |
| pesticide_5 | [12612073](https://www.pexels.com/photo/12612073/) |
| law_1 | [5387258](https://www.pexels.com/photo/5387258/) |
| law_2 | [7054502](https://www.pexels.com/photo/7054502/) |
| law_3 | [8815849](https://www.pexels.com/photo/8815849/) |
| law_4 | [7054505](https://www.pexels.com/photo/7054505/) |
| law_5 | [618158](https://www.pexels.com/photo/618158/) |
| import_1 | [14020705](https://www.pexels.com/photo/14020705/) |
| import_2 | [7519246](https://www.pexels.com/photo/7519246/) |
| import_3 | [262353](https://www.pexels.com/photo/262353/) |
| import_4 | [9806482](https://www.pexels.com/photo/9806482/) |
| import_5 | [20821680](https://www.pexels.com/photo/20821680/) |
| import_6 | [3277769](https://www.pexels.com/photo/3277769/) |
| veg_1 | [1458694](https://www.pexels.com/photo/1458694/) |
| veg_2 | [5425893](https://www.pexels.com/photo/5425893/) |
| veg_3 | [28991058](https://www.pexels.com/photo/28991058/) |
| veg_4 | [9705830](https://www.pexels.com/photo/9705830/) |
| veg_5 | [5425795](https://www.pexels.com/photo/5425795/) |
| veg_6 | [3987343](https://www.pexels.com/photo/3987343/) |
| fruit_1 | [3084068](https://www.pexels.com/photo/3084068/) |
| fruit_2 | [1352241](https://www.pexels.com/photo/1352241/) |
| fruit_3 | [9899252](https://www.pexels.com/photo/9899252/) |
| fruit_4 | [29823109](https://www.pexels.com/photo/29823109/) |
| fruit_5 | [30893357](https://www.pexels.com/photo/30893357/) |
| fruit_6 | [40495543](https://www.pexels.com/photo/40495543/) |
| supplement_1 | [13534594](https://www.pexels.com/photo/13534594/) |
| supplement_2 | [7615558](https://www.pexels.com/photo/7615558/) |
| supplement_3 | [3850691](https://www.pexels.com/photo/3850691/) |
| supplement_4 | [28100290](https://www.pexels.com/photo/28100290/) |
| supplement_5 | [3850712](https://www.pexels.com/photo/3850712/) |
| noodle_1 | [31286788](https://www.pexels.com/photo/31286788/) |
| noodle_2 | [4223948](https://www.pexels.com/photo/4223948/) |
| noodle_3 | [10913411](https://www.pexels.com/photo/10913411/) |
| noodle_4 | [10950869](https://www.pexels.com/photo/10950869/) |
| noodle_5 | [40000086](https://www.pexels.com/photo/40000086/) |
| noodle_6 | [1907227](https://www.pexels.com/photo/1907227/) |
| snack_1 | [31617910](https://www.pexels.com/photo/31617910/) |
| snack_2 | [37108654](https://www.pexels.com/photo/37108654/) |
| snack_3 | [34489907](https://www.pexels.com/photo/34489907/) |
| snack_4 | [38483963](https://www.pexels.com/photo/38483963/) |
| snack_5 | [33756116](https://www.pexels.com/photo/33756116/) |
| sauce_1 | [20843711](https://www.pexels.com/photo/20843711/) |
| sauce_2 | [40104203](https://www.pexels.com/photo/40104203/) |
| sauce_3 | [5899675](https://www.pexels.com/photo/5899675/) |
| sauce_4 | [1385185](https://www.pexels.com/photo/1385185/) |
| beverage_1 | [2479242](https://www.pexels.com/photo/2479242/) |
| beverage_2 | [10153721](https://www.pexels.com/photo/10153721/) |
| beverage_3 | [8356302](https://www.pexels.com/photo/8356302/) |
| beverage_4 | [30841170](https://www.pexels.com/photo/30841170/) |
| coffee_1 | [16682442](https://www.pexels.com/photo/16682442/) |
| coffee_2 | [12007828](https://www.pexels.com/photo/12007828/) |
| coffee_3 | [14807211](https://www.pexels.com/photo/14807211/) |
| tea_1 | [6870854](https://www.pexels.com/photo/6870854/) |
| tea_2 | [11669662](https://www.pexels.com/photo/11669662/) |
| tea_3 | [4390022](https://www.pexels.com/photo/4390022/) |
| honey_1 | [5634212](https://www.pexels.com/photo/5634212/) |
| honey_2 | [23940105](https://www.pexels.com/photo/23940105/) |
| honey_3 | [714522](https://www.pexels.com/photo/714522/) |
| honey_4 | [4921856](https://www.pexels.com/photo/4921856/) |
| oil_1 | [5737246](https://www.pexels.com/photo/5737246/) |
| oil_2 | [25745506](https://www.pexels.com/photo/25745506/) |
| oil_3 | [5056853](https://www.pexels.com/photo/5056853/) |
| seaweed_1 | [11963864](https://www.pexels.com/photo/11963864/) |
| seaweed_2 | [13555356](https://www.pexels.com/photo/13555356/) |
| seaweed_3 | [18019575](https://www.pexels.com/photo/18019575/) |
