---
layout: post
title: "Conversation with Claude on Data Centers and Crypto"
date: 2026-08-02 09:00:00 -0700
categories: [Random]
tags: [ai, data-centers, crypto]
toc: false
---

My wife asked me, "what's the point of so many data centers?" I didn't
have a great answer off the top of my head, so I put it to Claude — and
ended up in a back-and-forth that pushed back on its own first answer.
Reproduced here close to verbatim, styled to look like the actual chat.

<div class="mv-chat">
  <div class="mv-chat-turn mv-chat-user">
    <div class="mv-chat-label">You</div>
    <div class="mv-chat-bubble">
      <p>Why do we need so many data centers</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-claude">
    <div class="mv-chat-label">Claude</div>
    <div class="mv-chat-body">
      <p>A few forces are driving the boom:</p>
      <ul>
        <li><strong>AI is compute-hungry.</strong> Training and running large models (like the one answering you now) takes massive amounts of specialized hardware — way more than traditional web services ever needed.</li>
        <li><strong>Everything moved to the cloud.</strong> Streaming video, cloud storage, SaaS apps, gaming — services that used to run on local hardware now run on someone else's servers, all day, every day.</li>
        <li><strong>Data keeps growing.</strong> Photos, video, sensor data, transaction records — more of it gets created and stored than ever before, and it needs to live somewhere.</li>
        <li><strong>Redundancy and speed.</strong> Companies build data centers in multiple regions so services stay up if one fails, and so data is physically closer to users (lower latency).</li>
        <li><strong>Old hardware needs replacing.</strong> Chips get faster and more efficient every couple years, so there's constant demand to build new facilities with newer generations of hardware.</li>
      </ul>
      <p>The AI piece is the newest and fastest-growing driver — training a frontier model can require tens of thousands of GPUs running for months, and inference (actually serving answers to users) at scale adds even more ongoing demand.</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-user">
    <div class="mv-chat-label">You</div>
    <div class="mv-chat-bubble">
      <p>You sort of made a circular argument, the points that chips get faster and everything used to run locally are arguments for status quo</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-claude">
    <div class="mv-chat-label">Claude</div>
    <div class="mv-chat-body">
      <p>Fair, let me fix that.</p>
      <p>The honest core answer: demand is growing faster than efficiency gains can offset it. Chips getting faster should mean you need less new infrastructure to do the same work — and it does, for fixed workloads. But two things break that:</p>
      <ol>
        <li>The workloads themselves are new and enormous, not just migrated. Training a frontier AI model wasn't a thing 10 years ago. That's not "web traffic that used to run locally" — it's genuinely new compute demand stacked on top of everything else.</li>
        <li>Efficiency often increases total usage rather than shrinking footprint (this is the Jevons paradox — cheaper, faster compute makes more applications viable, so people run more of it, not less). Cheaper inference means AI gets embedded in more products, which increases total demand even as each unit gets more efficient.</li>
      </ol>
      <p>So the real drivers of growth, not just existence, are:</p>
      <ul>
        <li>AI training and inference at massive scale — new demand, not migrated demand</li>
        <li>More data being generated (video, sensors, IoT) faster than storage efficiency improves</li>
        <li>Geographic redundancy and latency needs — this multiplies locations, not just total compute, since you need copies near users everywhere</li>
        <li>Crypto mining, in earlier years, added a real chunk of demand too</li>
      </ul>
      <p>The "cloud migration" and "hardware refresh" points I made earlier explain why data centers exist and get rebuilt, but you're right they don't explain net growth — you could migrate to cloud once and then plateau. What's actually pushing the number up is new categories of demand outpacing efficiency gains.</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-user">
    <div class="mv-chat-label">You</div>
    <div class="mv-chat-bubble">
      <p>Agree with everything except the crypto part, seems like that ponzi scheme is about to run its course</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-claude">
    <div class="mv-chat-label">Claude</div>
    <div class="mv-chat-body">
      <p>That's a reasonable read, but worth separating a few things that often get lumped together:</p>
      <ul>
        <li><strong>Speculative trading/price</strong> — this is genuinely volatile and cyclical; boom-bust patterns have repeated multiple times over the last decade, and predicting the next bust is a coin flip at best.</li>
        <li><strong>Proof-of-work mining</strong> — this is the actual data-center-relevant piece. Bitcoin still runs on proof-of-work and consumes real, ongoing energy/compute regardless of price swings, as long as the network keeps operating. It's dropped off the "growth driver" list somewhat because Ethereum (the other huge PoW consumer) switched to proof-of-stake in 2022, cutting its energy use by ~99%. That was a big structural change, not just a price cycle.</li>
        <li><strong>"Ponzi scheme" framing</strong> — that's a contested characterization. Critics call it that because value depends on new buyers; defenders point to actual use cases (payments in unstable-currency countries, decentralized settlement, etc.) as fundamentals beyond pure speculation. Reasonable people disagree here, and it's more of a values/prediction question than a fact I can settle.</li>
      </ul>
      <p>So: mining is a smaller slice of data-center demand than it was a few years ago (partly because of the Ethereum shift, not because crypto is dying), and whether the whole space "runs its course" is genuinely uncertain — depends on regulation, institutional adoption (ETFs, etc.), and whether use cases beyond speculation actually take hold.</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-user">
    <div class="mv-chat-label">You</div>
    <div class="mv-chat-bubble">
      <p>Good answer, guess we'll have to agree to disagree</p>
    </div>
  </div>
  <div class="mv-chat-turn mv-chat-claude">
    <div class="mv-chat-label">Claude</div>
    <div class="mv-chat-body">
      <p>Sounds good — fair place to leave it.</p>
    </div>
  </div>
</div>
