# How To Use

## Exporting WhatsApp chat
1. On your phone, go to the chat with your friend you want to get interesting stats on.
2. On the chat window, tap the top rightmost icon (three vertical dots). Tap on "More" and then select "Export Chat".
3. Since we only analyse text as of now, select "Without Media" and save on the extra data usage.
4. Select the app you want to use to export, preferably email. Complete the email and send.
5. In your inbox, you should see a mail with the chat text as attachment. WhatsApp also treats the contacts sent as "non-media" files so they will be present too. Ignore them and download the chat to your hard drive.

## Running whatsapp-chatstats
1. Make sure you have jupyter notebooks installed.
2. Clone this repo. You can also just copy the whatsapp-chatstats.ipynb notebook text and create a ipython notebook locally.
3. In the directory where you have the downloaded notebook, run "jupyter notebook". The notebook should open in a browser. 
4. In the notebook, modify the "filepath" field to enter the path of your downloaded chat in the above section.
5. Lastlty, from the jupyter notebook toolbar, select "Cell" and then "Run All".
6. You should be able to see all chat statistics in the notebook itself. As of now, the plots open in a separate browser tab.
