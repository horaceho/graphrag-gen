# GraphRAG GEN (創世記)

A sample GraphRAG project of the GEN (創世記) chapter in Bible.

Setup `.env`
```
GRAPHRAG_API_KEY={API_KEY}
```

`query`
```base
graphrag query \
--root . \
--method global \
--query "故事的中心思想是什麼？"
```

The chapter text is from [新標點和合本 cmn-cu89t](https://github.com/horaceho/bibles/). 

### Branches
- [記承天寺夜遊](https://github.com/horaceho/graphrag-gen/tree/ollama-deepseek-bge-m3) local `deepseek-r1:8b` chat model with `bge-m3` embedding model.
