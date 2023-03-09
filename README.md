# streamlit-docker
<img src="image/Streamlit.png" width="200">
streamlit docker


## Contents
* [Basic docker operations](#basic-docker-operations)
* [Streamlit](#streamlit)
* [Reference](#reference)



## [Basic docker operation](https://github.com/fuyu-quant/dockerfile-for-data-scientists)


## Streamlit

### Streamlitの起動
* コンテナ起動時に起動


* コマンドで起動
```bash
# コンテナ外部から起動
docker-compose exec streamlit bash "streamlit run src/app.py --server.port=8060 --server.address=0.0.0.0"

# コンテナ内部から起動
streamlit run src/app.py --server.port=8060 --server.address=0.0.0.0
```
When you want to exit, press [control + c]
* Link
http://127.0.0.1:8060/

## Reference
* https://streamlit.io/
* https://docs.streamlit.io/