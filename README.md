# testing

# اسکریپت پایتون برای ایجاد انیمیشن ASCII
import time

frames = [
    r"""
     ██████╗ 
    ██╔════╝ 
    ██║  ███╗
    ██║   ██║
    ╚██████╔╝
     ╚═════╝ 
    """,
    r"""
     ██████╗ 
    ██╔════╝ 
    ██║  ███╗
    ██║   ██║
    ╚██████╔╝
     ╚═════╝ 
    """
]

for _ in range(10):
    for frame in frames:
        print("\033[H\033[J") #
        print(frame)
        time.sleep(0.5)


+f after soo ++.....htt
