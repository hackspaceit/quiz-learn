# GPT Prompt

Come up with entertaining quiz content for topic: **[YOUR_TOPIC]**.

It is highly important to follow these rules during quiz creation:
- No more than 60 symbols for the description.
- The minimum and maximum number of answers is 3. No more, no less.
- The length of the answer should be no more than 8 symbols.
- Default amount of questions is 20.

Required structure of the quiz.

```json
{
  "shortDescription": "Test your knowledge of blockchain history with this quiz.",
  "questions": [
    {
      "question": "Who created Bitcoin?",
      "answers": ["Nakamoto", "Buterin", "Wright"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is the first blockchain?",
      "answers": ["Bitcoin", "Ethereum", "Ripple"],
      "correctAnswerIndex": 0
    },
    {
      "question": "When was Bitcoin created?",
      "answers": ["2009", "2010", "2011"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a block?",
      "answers": ["Data", "Node", "Chain"],
      "correctAnswerIndex": 0
    },
    {
      "question": "Which language is used in Ethereum?",
      "answers": ["Solidity", "Rust", "Python"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is mining?",
      "answers": ["Validating", "Storing", "Sending"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a smart contract?",
      "answers": ["Program", "Coin", "Wallet"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a DApp?",
      "answers": ["App", "Database", "Protocol"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a node?",
      "answers": ["Computer", "Coin", "Block"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is DeFi?",
      "answers": ["Finance", "Coin", "Protocol"],
      "correctAnswerIndex": 0
    },
    {
      "question": "Who is Vitalik Buterin?",
      "answers": ["Ethereum", "Bitcoin", "Ripple"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is proof-of-work?",
      "answers": ["Consensus", "Coin", "Block"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a fork?",
      "answers": ["Split", "Coin", "Block"],
      "correctAnswerIndex": 0
    },
    {
      "question": "When was Ethereum launched?",
      "answers": ["2015", "2014", "2016"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a hash?",
      "answers": ["Code", "Data", "Coin"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is blockchain?",
      "answers": ["Ledger", "Coin", "Node"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is gas in Ethereum?",
      "answers": ["Fee", "Coin", "Block"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is a private key?",
      "answers": ["Password", "Coin", "Block"],
      "correctAnswerIndex": 0
    },
    {
      "question": "What is Ripple?",
      "answers": ["Payment", "Coin", "Node"],
      "correctAnswerIndex": 0
    },
    {
      "question": "Who is Nick Szabo?",
      "answers": ["Smart", "Coin", "Node"],
      "correctAnswerIndex": 0
    }
  ]
}

```

Any deviations from these rules will result in a failed quiz.
After creating a quiz.json the content of the file in code tag.
