# Multi-turn-RAG
09.11.2025 trying to upload files, BM25 retrieval for one benchmark  
14.11.2025 finish the baseline by using BM25  
To do: trying dense indexing

Done:  
1. Upload the dataset into Github 
2. using git LFS to upload indexes.zip,  
please install git LFS before clone (basically the index for BM25 is fixed, so please run the code from BM25_all.py to get the index and please make sure you have indexes directory)
3. Using all the corpus to do the BM25 retrieval, also writing as method to read relative path, cmd code, evaluation etc. on BM25_all.py

temp:
bm25中的split我这边改成了train才跑出来，看看是否需要改回dev。
bge的indexes和bm25的不一样
bge做dense embedding太大，拿公司电脑跑一下