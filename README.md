# ringbitcar-ko

This package is based on [tinkertanker/pxt-ringbitcar](https://github.com/tinkertanker/pxt-ringbitcar.git).

## Modifications in this package

### English

1. **set_motor_speed function**  
   A configurable motor speed (20%, 30%, 50%, 70%, 100%) was added. When the motor is driven repeatedly at full speed, it can overload; travel distance and rotation angle then vary run-to-run. This change lets you lower the default speed (e.g. 70%) to reduce load and get more consistent movement. In other words, it attempts to improve a hardware limitation (Thermal overload) through software (speed regulation).

2. **Korean locale**  
   Korean locale was added. Block labels and help text are available in Korean when the editor language is set to Korean. Locale files: `_locales/ko/RingbitCar-strings.json`, `_locales/ko/RingbitCar-jsdoc-strings.json`.

3. **Bug fix for Ultrasonic Block** 
Fixed an issue where the ultrasonic distance block was not translated correctly.
---

### 한글

1. **set_motor_speed 함수**  
   모터 속도를 선택 가능하도록(20%, 30%, 50%, 70%, 100%) 추가했습니다. 기존 코드로 여러 번 동작시키면 모터가 과부하되어, 매번 이동 거리와 회전각이 달라지는 현상이 있었습니다. 기본 속도를 낮춰(default: 70%) 모터에 가해지는 부하를 줄이고 동작을 일정하게 만들려는 시도이며, 하드웨어적 한계(모터 과부하)를 소프트웨어(속도 규제)로 완화하고자 했습니다.

2. **한국어 로케일**  
   한국어 번역을 추가했습니다. 브라우저 언어가 한국어일 경우 언어를 블록 문구와 도움말이 한국어로 표시됩니다. 로케일 파일: `_locales/ko/RingbitCar-strings.json`, `_locales/ko/RingbitCar-jsdoc-strings.json`.

3. **초음파 블록 버그 수정** 
초음파 거리 블록의 번역이 적용되지 않던 문제를 수정했습니다.
---

## License
MIT

## Supported targets
for PXT/microbit (The metadata above is needed for package search.)

