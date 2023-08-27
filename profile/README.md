# iApps - from zero to hero

Step 1: Environment Setup

Create a virtual environment and activate it.
Install required packages using pip.

Step 2: Hello World

Create a Streamlit application in a Python file (app.py).
Import the Streamlit library and define a function to display a welcome message.

Step 3: Modular Design

Create a separate Python file (modules.py) to organize modular code.
Move the display_hello function to modules.py.
Import display_hello from modules.py into app.py.

Step 4: UI/UX

Enhance the UI by adding user input elements like buttons and text inputs.
Utilize the Streamlit functions to create user-friendly interaction.

Step 5: AI Integration

Integrate a basic machine learning model from your choice of models.
For instance Use CountVectorizer and Multinomial Naive Bayes classifier to implement the predict_spam function for spam prediction.

Step 6: Language Model Extensions

Utilize the Transformers library to add a text summarization feature.
Implement the summarize_text function for text summarization from BART

Step 7: Security Best Practices

Implement input validation and sanitization using regular expressions.
Use the sanitize_input function to ensure safe user inputs.

Step 8: Deployment

Choose a deployment platform such as AWS, GCP, or DigitalOcean.
Prepare your code for deployment by creating a requirements.txt file.
Configure a web server (Nginx or Apache) to handle requests.
Start the Streamlit app and make it accessible online.
The following code has been extracted from the official cheatsheet and is posted here to save time on rapid deployment</a><br />

# installation and running
```bash
streamlit run your_script.py
```
# pre-release features
```bash
pip uninstall streamlit
pip install streamlit-nightly --upgrade
```
# command line
```bash
streamlit --help
streamlit run your_script.py
streamlit hello
streamlit config show
streamlit cache clear
streamlit docs
streamlit --version
```

# display text and markdown
```python
st.text('Fixed width text')
st.markdown('_Markdown_')
st.latex(r''' e^{i\pi} + 1 = 0 ''')
st.write('Most objects')
st.title('My title')
st.header('My header')
st.subheader('My sub')
st.code('for i in range(8): foo()')
```
# data display
```python
st.dataframe(my_dataframe)
st.table(data.iloc[0:10])
st.json({'foo':'bar','fu':'ba'})
st.metric('My metric', 42, 2)
```
# media display
```python
st.image('./header.png')
st.audio(data)
st.video(data)
```
# buttons and controls
```python
st.button('Click me')
st.checkbox('I agree')
st.toggle('Enable')
```
# import convention
```python
import streamlit as st
```

# import convention
```python
import streamlit as st
```
# import convention
```python
import streamlit as st
```

# import convention
```python
import streamlit as st
```

# import convention
```python
import streamlit as st
```

# import convention
```python
import streamlit as st
```

# import convention
```python
import streamlit as st
```



