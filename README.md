# TAJA.HOTO.DEV 맵 만들기
taja.hoto.dev에 사용되는 맵을 만드는 방법입니다.


```
/// 예시: https://taja.hoto.dev/map/seventeen-very_nice.json

{
    "title":"세븐틴 - 아주 NICE",
    "music_file":"https://taja.hoto.dev/map/music/SEVENTEEN-Very_NICE.mp3",
    "artist":"SEVENTEEN[세븐틴]",
    "map_builder":"맵 제작자",
    "subtitle":"next",
    "language":"kor",
    "m_data" : [
        {
            "start":0,
            "text": "",
            "sub_text": ""
        },
        {
            "start":3760,
            "text": "아침엔 모닝콜 필수던 내가",
            "sub_text": "아침엔 모닝콜 필수던 내가"
        },
        {
            "start":7571,
            "text": "오늘은 번쩍 번쩍 눈이 떠지는가",
            "sub_text": "오늘은 번쩍 번쩍 눈이 떠지는가"
        },
        {
            "start":11505,
            "text": "데이트 날이라 그런지",
            "sub_text": "데이트 날이라 그런지"
        },
        {
            "start":13964,
            "text": "어제 꿈도 좋은 꿈 꿨지",
            "sub_text": "어제 꿈도 좋은 꿈 꿨지"
        },
        {
            "start":16177,
            "text": "새 신발을 신고",
            "sub_text": "새 신발을 신고"
        },
        {
            "start":18144,
            "text": "",
            "sub_text": "(현관문을 열고 나가면)"
        },
        {
            "start":20111,
            "text": "오늘 날씬 너를 많이 닮아",
            "sub_text": "오늘 날씬 너를 많이 닮아"
        },
        
        (...생략...)
        
        ,
        {
            "start":55764,
            "text": "__{END}__",
            "sub_text": ""
        }
    ]
}
```

```title```: 노래의 제목입니다<br>
```music_file```: 노래(mp3)의 파일 위치 입니다<br>
```artist```: 해당 노래를 부른 가수(그룹)이름 입니다<br>
```map_builder```: 해당 맵파일을 제작하신분 입니다<br>
```subtitle```: 가사위에 작은 글씨 표시 여부입니다. [```slient```,```next```]<br>
```language```: 타자를 칠 언어입니다. 한/영 변환이 없으므로, 한 언어로만 작성해주셔야 합니다. [```kor```, ```eng```]<br>
<br>
```m_data```: 맵 노트들이 있는 배열입니다.<br>
```start```: 해당 노트가 시작될 시간(milisecond)입니다.<br>
```text```: 타자를 쳐야할 문자열입니다.<br>
```sub_text```: 타자 위에 작게 나타나는 문자입니다. ```subtitle```여부에 따라 표시 방법이 다릅니다.<br>
