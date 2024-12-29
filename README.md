# Diversity Train Set 다양성 열차세트 /DTS
![DTS_board](https://github.com/DTS-NewGRF/DTS/blob/minengallery/docs/DTS_board.png)
**다양성 열차세트**는 <br>
약 2016년에 [YST set](https://github.com/evepoi/YST)에서 최초로 시작했다.<br>
2022년 4월 2일 `[YST]는 중단되었다.`<br>
2023년 5월 `Derivative Train Set 파생형 열차세트 / DTS`로 다시 통합하여 진행을 시작했다.<br>
2024년 1월 `Diversity Train Set 다양성 열차세트 / DTS`로 이름을 변경하여 다양한 열차들을 수용하는데 적극적으로 추가진행하고 있다.<br>
[Github release 페이지](https://github.com/DTS-NewGRF/DTS/releases)와 인게임 온라인 컨텐츠에서 다운받을 수 있습니다.<br>

## 공지사항
```
[공지사항] 1.60 릴리즈 공개까지 공지.
[도색삭제] 즉시 제거처리
[열차전체삭제]
1단계 : 해당 릴리즈 모든 기후 사용금지처리
2단계 : [다음 버전 릴리즈] 삭제 그래픽 적용
3단계 : [다음 버전 릴리즈] 일괄삭제처리
```
## 최근 등록 프리 릴리즈
```
[1.60] 2024.12.29
[추가]
- [가상] KTX-청룡 JR 도색 16량
- [가상] KTX-온누리 16량
- [기관차] 4400호대 교외선 도색
- [교외선] 객차, 발전차
[변경]
- [성능] 신칸센 E2, 500, 700계 가상 고속열차 속도 매겨변수 적용
- [그래픽] 템플릿 오류 일괄 수정 (열차길이 7을 쓰는 고속열차 차량)
- [이름변경] HYEL-200->HYEL-무궁화 / HYEL-220->HYEL-무궁화 DD
- [그래픽] 무궁화 일반실 객차 (장대형 신도색 방송실 개조)
- [그래픽] 레이디버드, 유선형 발전차 일부
[삭제진행]
- E6 + E5 & H5 삭제 그래픽 적용 / (1.61) 일괄 삭제처리
```

## 최근 등록 릴리즈
```
[1.59] 2024.12.12
[추가]
- [가상열차] KTX-온누리 (8, 10량)
- [그룹화] ITX, KTX, 누리로, AREX, MTR, 한큐전철, 니시테츠, CRH, HYEL
- [특수] 투명기관차 / 수용량0, 유지보수비0, 속도 20km/h
- [진열용] 평판화차, 평판유조, 평판화차-미국형, 평편화차-포터2 / 수송량0
- [화물] 소화물차 추가
- [그룹화] 한국 수화물차
- [신칸센] E5&H5 + E8 중련
- [NKX] 최고속도 260km/h 도색개조로 추가 / 4량 추가 (150km/h 고정)
[변경]
- [통일호] 객차 등장년도에 따른 그래픽 오류 수정
- [이름변경] 기존 한국 수화물차->고속수화물차 (Express Luggage Car) / NKX -> DTX-소백 / HMX -> DTX-태백
- [도색] 다른 열차 뒤에 붙을 경우 기본도색으로 변경되는 CDC, 공항철도 1000호대 오류 수정
- [템플릿] 통일화 및 정렬
- [그래픽] DTX-소백, DTX-태백
- [그래픽] 템플릿 정렬에 의한 발전차 재조정
[삭제진행]
- E6 + E5 & H5 모든 기후 사용금지 처리/ (1.60) 삭제 그래픽 적용 / (1.61) 일괄 삭제처리
[삭제]
- [신칸센] E6 그룹화
```

## 인게임 등록
```
[1.50.1] 2024.06.17
[추가]
- [NKX] 10량 추가 및 그룹화
- [HMX] 10량 추가 및 그룹화

[변경]
- 저작권 CC-BY-NC-SA 3.0 사용하므로 저작권 관련 변경하여 다시 업로드 합니다.
```

## Next 인게임 버전 : 1.60

## 등록기준
### 공통사항
기본 템플릿과 일치하지 않을 경우 적용이 보류된다. 하지만, 그외 자료는 제한을 두지 않고, 적용하고 있다.

### 깃허브 릴리즈 및 온라인컨텐츠 등록
기본 자료는 본 깃허브 릴리즈를 통해 메인 업로드를 기준으로 한다. <br>
릴리즈 등록시 프리 릴리즈가 아닌 최종 릴리즈로 등록된다. <br>
온라인 컨텐츠는 매달 등록되는것으로 정의한다. <br>
매달 기준 최종 깃허브 릴리즈가 온라인컨텐츠로 등록되는 것과 같다. <br>

## 개발
### 빌드하는 방법
이 NewGRF를 빌드하려면 [NML](https://github.com/OpenTTD/nml)과 **Python 3**이 필요합니다. <br> 
터미널 쉘에서 ``make``를 실행하세요. Windows 환경이라면, 그 전에 명령 프롬포트를 열고 ``bash``를 입력하세요.  <br>
``make clean``을 입력하면 모든 생성된 파일이 초기화됩니다.

## 저작권
### CC-BY-NC-SA v3.0 사용함.