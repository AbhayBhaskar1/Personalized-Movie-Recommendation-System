<!DOCTYPE html>
<html lang="en">
<body>

  <h1>Personalized Movie Recommendation System</h1>

  <h2>Project Overview</h2>

  <p>This project implements a personalized movie recommendation system using data analysis and natural language processing (NLP) techniques. The system recommends movies to users based on their preferences, leveraging movie descriptions and genres.</p>

  <h3>Key Components and Workflow</h3>

  <h4>Data Preparation</h4>

  <ul>
    <li><strong>Data Extraction:</strong> Utilized Python's pandas library for efficient data handling.</li>
    <li><strong>Movie Details:</strong> Extracted movie IDs, titles, overviews, and genres from the dataset.</li>
  </ul>

  <h4>Natural Language Processing (NLP)</h4>

  <ul>
    <li><strong>Text Processing:</strong> Employed CountVectorizer to tokenize and convert movie descriptions into a matrix of token counts.</li>
    <li><strong>Similarity Measurement:</strong> Used cosine similarity to quantify the similarity between movie descriptions, enabling effective recommendation based on textual content.</li>
  </ul>

  <h4>Recommendation Function</h4>

  <ul>
    <li><strong>Function Development:</strong> Created a recommendation function that analyzes movie indices and similarity scores.</li>
    <li><strong>Personalization:</strong> Ensured the system adapts to evolving user tastes, providing tailored movie recommendations over time.</li>
  </ul>

  <h4>User Interface</h4>

  <ul>
    <li><strong>Streamlit Integration:</strong> Developed an intuitive user interface using Streamlit.</li>
    <li><strong>User Experience:</strong> Focused on creating a seamless and visually appealing navigation experience for users.</li>
  </ul>


  <h3>Technologies and Tools Used</h3>

  <ul>
    <li><strong>Programming Language:</strong> Python</li>
    <li><strong>Libraries:</strong> pandas for data manipulation, scikit-learn for NLP and similarity calculations, Streamlit for the user interface.</li>
  </ul>





  <h3>How to Run</h3>

  <p>To run the Personalized Movie Recommendation System locally, follow these steps:</p>

  <ol>
    <li><strong>Clone the repository:</strong>
      <pre>git clone https://github.com/your_username/PersonalizedMovieRecommendation.git</pre>
    </li>
    <li><strong>Navigate to the project directory:</strong>
      <pre>cd PersonalizedMovieRecommendation</pre>
    </li>
    <li><strong>Install dependencies:</strong>
      <pre>pip install -r requirements.txt</pre>
    </li>
    <li><strong>Run the Streamlit app:</strong>
      <pre>streamlit run app.py</pre>
    </li>
    <li><strong>Open your browser:</strong>
      <pre>http://localhost:8501</pre>
    </li>
  </ol>



</body>
</html>
