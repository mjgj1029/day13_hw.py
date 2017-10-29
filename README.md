# day13_hw.py
import turtle as t       # 거북이 함수를 사용.
import random            # random 함수를 사용.

t.bgcolor("black")       # 배경색 검은색으로 지정.
t.color("white")         # 펜색 흰색으로 지정.

t.shape("turtle")        # 펜모양 거북이로 지정.
t.speed(0)               # 거북이속도 가장 빠르게.

t.up()                   # 꼬리를 올려 펜 자취 숨기기.
t.goto(250, 250)         # 좌표 (250, 250)으로 이동.
t.down()                 # 꼬리를 내려 펜 자취 보이기.
