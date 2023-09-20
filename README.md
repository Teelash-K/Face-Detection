# Face-Detection

<h2>Instructions</h2>
<ol><li>Add instructions to the Streamlit app interface to guide the user on how to use the app.</li>
<li>Add a feature to save the images with detected faces on the user's device.</li>
<li>Add a feature to allow the user to choose the color of the rectangles drawn around the detected faces.</li>
<li>Add a feature to adjust the minNeighbors parameter in the face_cascade.detectMultiScale() function.</li>
<li>Add a feature to adjust the scaleFactor parameter in the face_cascade.detectMultiScale() function.</li></ol>

<h3>Hints:</h3>

Use the st.write() or st.markdown() functions to add instructions to the interface.

<ol><li>Use the cv2.imwrite() function to save the images.</li>
<li>Use the st.color_picker() function to allow the user to choose the color of the rectangles.</li>
<li>Use the st.slider() function to allow the user to adjust the minNeighbors parameter.</li>
<li>Use the st.slider() function to allow the user to adjust the scaleFactor parameter.</li>
