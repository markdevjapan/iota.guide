---
title: "How to Generate Iota Wallet Seed"
date: 2019-09-30T22:52:23+01:00
draft: false
aliases:
    - /seed/how-to-generate-iota-wallet-seed/
    - /article/how-to-generate-iota-wallet-seed/
---

<div class="wrapper" id="top-wrapper">
	<div class="container pt-5 text-center">
		<div class="row pt-5">
			<div class="col">
				<h1 class="mb-3"><a href="{{< baseurl >}}/article/how-to-generate-iota-wallet-seed">How to generate your IOTA Wallet Seed</a></h1>
			</div>
		</div>
	</div>
</div>

<div class="container mt-5">
    <main class="col">
        <div class="row">
            <h2>Generate your seed on linux:</h2>
            <pre><code>cat /dev/urandom |tr -dc A-Z9|head -c${1:-81}</code></pre>
            <h2>Generate your seed on Mac:</h2>
            <p>Open Terminal and type or paste the following then press enter:</p>
            <pre><code>cat /dev/urandom |LC_ALL=C tr -dc 'A-Z9' | fold -w 81 | head -n 1</code></pre>
            <h2>Generate your seed online:</h2>
            <p>We used to link to a website here but not any more. It is no longer safe to use any website to generate your IOTA seed as many sites have been found to be malicious and unsafe. Instead, if you want to generate your IOTA Seed, download the Trinity wallet and use the in-build feature</p>
        </div>
    </main>
</div>