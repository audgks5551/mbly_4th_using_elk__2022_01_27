FROM elasticsearch:7.16.3
RUN bin/elasticsearch-plugin install --batch analysis-nori ## 한글 형태소 분석기
RUN bin/elasticsearch-plugin install --batch https://github.com/audgks5551/javacafe-analyzer-7.16.3/raw/master/javacafe-analyzer-7.16.3.zip ## 초성검색, 한영검색, 연관검색 기능을 위해