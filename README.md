<h1>Solana Twitter</h1>
	<p>Solana Twitter is a decentralized social media application built on the Solana blockchain using Rust and Anchor framework. Users can log in with their wallets to send tweets up to 280 characters and add an optional "topic" field to help search for tweets. The application also allows users to view all tweets or filter their search by author or topics.</p>

<h2>Features</h2>
<ul>
	<li>Integration with various wallets</li>
	<li>User authentication with wallet connection</li>
	<li>Sending tweets up to 280 characters</li>
	<li>Adding optional "topic" field to tweets</li>
	<li>Viewing tweets without logging in</li>
	<li>Filtering tweets by author or topics</li>
</ul>

<h2>Implementation</h2>
<p>Tweets are stored as individual Solana accounts, making them public on the blockchain. Users pay for transaction fees and storage required to hold their tweets on the blockchain. The Anchor framework is used to improve the development experience and RPC calls are made to the Solana blockchain via Anchor's JavaScript library to fetch and filter tweets on the blockchain.</p>

<h2>Technologies Used</h2>
<ul>
	<li>Rust</li>
	<li>Anchor framework</li>
	<li>Vue.js</li>
	<li>Web3.js</li>
	<li>Mocha</li>
</ul>