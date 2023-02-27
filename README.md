# BOJ
-BOJ(Baekjoon Online Judge)
백준 온라인 저지( https://www.acmicpc.net/ ) 에서 해결한 문제들을 업로드합니다.

-설명이 필요한 문제는 커밋 코멘트에 설명을 적어뒀습니다.
   -> 커밋 코멘트로는 text로만 설명이 가능하다는 점 때문에, 2021-09-22 이후 작성한 것들은 nahwasa.com 블로그에 작성중입니다. 차후 전부 옮길 예정.

-N 폴더에는 'N ~ N+99'번까지의 문제 중 제가 푼 문제가 들어있습니다. (ex - 02300 폴더 : 2300번~2399번)

-올리면 안되거나, 올릴 의미가 없는 문제는 올리지 않습니다. (백준 7대난제, 랜덤게임 종류 등)

-.java : 자바 / .cs : C# / .py : 파이썬 /  등

```mermaid
classDiagram
      Animal <|-- Duck
      Animal <|-- Fish
      Animal <|-- Zebra
      Animal : +int age
      Animal : +String gender
      Animal: +isMammal()
      Animal: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Fish{
          -int sizeInFeet
          -canEat()
      }
      class Zebra{
          +bool is_wild
          +run()
      }
```
