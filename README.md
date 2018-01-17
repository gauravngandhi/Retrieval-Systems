CS6200-Project 

===============================================================================
SETUP:
  
2) Import the project into one of the IDEs (Eclipse, Intellij) and run Index.java:<br/>
  a) Import the project into your IDE.<br/>
  b) Run Index.java as a Java application.<br/>

===============================================================================
Flowchart of Index.java<br/>
<ol>
  <li>Phase 1: Indexing, retrieval systems, Pesudo Relevance Feedback, Baseline runs using stop word list and Stemmed corpus.
    <ol> 
      <li>Task 1: Indexing and retrieval systems
        <ol>
          <li>Parse the documents and create a word unigram inverted Index</li>
          <li>Perform baseline (BM25, tf-idf, smoothed query likelihood and lucene) run
            <ol>
              <li>BM25 retrieval model</li>
            </ol>
          </li>
        </ol>
      </li>
    </ol>
  </li>
</ol>
  1. Task 1: Indexing, retrieval systems.<br/>
    1. Parse the documents and create a a word unigram inverted index<br/>
    2. Perform baseline (BM25, tf-idf, smoothed query likelihood and lucene) runs.<br/>
      1. BM25 retrieval model.<br/>
      2. TF-IDF retrieval model.<br/>
      3. Smoothed Query likelihood retrieval model.<br/>
      4. Lucene retrieval model.<br/>
        
    2. Task 2: Pesudo Relevance feedback (Note: Smoothed query lilihood retrieval system is used).<br/>
    3. Task 3: Baseline runs using stopp word list and Stemmed corpus.<br/>
    
      	
2. Phase 2: Snippet Generation on the results of smoothed query likelihood.<br/>
  3. Phase 3: Evaluation on 4 baseline runs, 1 query refinement run (PRF) and 3 stopped runs.<br/>
   


