https://pypi.org/project/worldstock/
pip install worldstock을 통해 설치

해당 패키지는 크게 두가지 기능으로 이루어져 있다.
1. 국가별 상장 종목 리스트를 가져오는 기능
2. 가져온 종목의 이름을 전처리하여 요약된 이름 혹은 alias이름을 만드는 기능

* 1번 기능을 통하여 선택한 국가에 상장된 종목들의 이름과 재무정보, 기업개요 등을 가져올 수 있다.
* 2번 기능에서는 1번 기능에서 가져온 상장 종목의 이름을 사회에서 통용되는 이름으로 변경한다. 
ex) The Procter & Gamble Company -> P&G 

이때, 전처리를 위해 여러 과정을 거치며 수작업 데이터 또한 포함된다. 

The package consists of two main functions.
1. Ability to obtain a list of listed stocks by country
2. Ability to preprocess the names of imported items and create summarized names or aliases

* Through function 1, the names, financial information, and corporate overview of the stocks listed in the selected country can be brought.
* In function 2, the name of the listed item taken from function 1 is changed to a common name in society.
ex) The Procter & Gamble Company -> P&G
In this case, manual data is also included through various processes for preprocessing.
