# test -1
깃허브 사용법을 연습합니다.

여기에 원하는 내용을 입력하세요.

작성한 소스에 대한 간단한 소개글을 작성합니다.

여기에 원하는 내용을 입력하세요.

작성한 소스에 대한 간단한 소개글을 작성합니다.

한줄짜리 소스 코드는 `function add(x, y) { retrun x + y; }` 처럼 사용합니다.

소스 코드 삽입하기

```
data = """
park 800905-1049118
kim  700905-1059119
"""

result = []
for line in data.split("\n"):
    word_result = []
    for word in line.split(" "):
        if len(word) == 14 and word[:6].isdigit() and word[7:].isdigit():
            word = word[:6] + "-" + "*******"
        word_result.append(word)
    result.append(" ".join(word_result))
print("\n".join(result))
```
코드 입력 끝!
