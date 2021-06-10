# final-year-project

<p> 1. Run RASA RESTful API.ipynb notebook :warning: except the last 3 cells  </p>
<p>2. Run the 1st cell out of the last 3. Then, copy the generated ngrok link and paste it as FetchAPI's POST URL. Ex: <code><NGROK_LINK>/requests</code> .Make it to https.</p>
<p>3. Expose React Website using <code>lt --port PORT NUMBER</code>. Then copy the generated link and paste in the second last cell.</p>
<p>4. Run the rasa server using <code>rasa run -m models --enable-api --cors “*” --debug</code>.</p>
<p>5. Expose the RASA server using <code>./ngrok http 5005</code> & copy the generated https link and paste in the second last cell.</p>
<p>6. Now run the second and third last cell in order.</p>
<p>7. Use the chatbot in the tunnelled website URL for Q & A.</p>
