# FlexSettle
An AI-powered grid settlement engine for DER aggregators participating in wholesale energy markets under FERC Order 2222.

## Repository organization
```
FlexSettle/
├── data/
│   ├── raw/            # Original unmodified PDFs
│   └── processed/      # Extracted/cleaned outputs
├── docs/
├── src/
│   ├── agents/
│   ├── market/
│   ├── settlement/
│   └── dashboard/
├── tests/
├── notebooks/          # Jupyter notebooks for exploration/demos
├── .env.example        # Template showing required keys (no real values)
├── .env                # Real keys (add to .gitignore)
├── .gitignore
├── requirements.txt
└── README.md
```

.env example
```
ANTHROPIC_API_KEY=your-key-here
PJM_API_KEY=your-key-here
```
