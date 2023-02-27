<h1>Blockchain-based-File-Storage</h1>



<h2>How to run the application</h2>

1. Install required libraries using :
   `pip install -r requirements.txt`
2. Open one terminal and start server/peer:
   `python peer.py`
3. Open another terminal and start a client:
   `python run_app.py`
4. Copy the link from the client terminal and paste it in any browser.
5. To run our experiment of different Proof of Work concepts:
`python POW_Comparison.py`
<h2> Project Information </h2>
We developed a web-based application for decentralized file storing using blockchain. In this application any user can upload as many files(one at a time) as he/she likes. All other peers and the user himself can download and access those file in their system. File can be of any type and any size. Refer to project demo link to see the detailed explanation. <br />
We are using randomly generated nonce in proof of work concept to acheive the required difficulty (diff = 3). Once peer uploads the file, the file is stored in a block including username, filesize and file data. These block gets appended to the current blockchain, which makes it impossible to edit or delete the file/block.<br /> 
The reason to implement file storing using blockchain is its abilitiy to avoid any modification or deletion. No one can delete or corrupt our files that are stored.
