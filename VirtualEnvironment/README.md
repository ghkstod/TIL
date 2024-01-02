# conda&PyCharm Python가상환경 설정 + VisualStudio Python가상환경 설정

## 1. conda&PyCharm

아나콘다 프롬포트와 PyCharm을 이용해서 가상환경을 설정하는 방법

1. 아나콘다 프롬포트 실행

(imagehttps://private-user-images.githubusercontent.com/134246762/293702785-f5c6cd6d-2715-4e7e-8fdc-bf728b8dbcdd.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDQyMDI2NDcsIm5iZiI6MTcwNDIwMjM0NywicGF0aCI6Ii8xMzQyNDY3NjIvMjkzNzAyNzg1LWY1YzZjZDZkLTI3MTUtNGU3ZS04ZmRjLWJmNzI4YjhkYmNkZC5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwMTAyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDEwMlQxMzMyMjdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT04NjcxNDg2ZGY5Yzc5ZGRiZjNiNTM5Yjk4Y2UwMzRiMmQxNGYzM2U5YWM2ZGY5Mzc3NDNiNzc2NjkwZmEzMjA3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.8nwKRPdxPiITjupq5Sywn6aEzoIkY_W29xxNygTw9cc)

2.conda create -n virtualenvironmentname python=version(ex.3.10)

<image>

3.conda activate virtualenvironmentname 

<image>

4.conda install packagename1 packagename2 packagename3 ... packagenamen

<image>

5.비어있는 새 폴더 생성

6.PyCharm에서 폴더 접근

<image>

7.setting-> python interpreter -> add interpreter -> conda Environment -> virtualenvironmentname

<image>

8.가상환경 설정완료 및 테스트

<image>
