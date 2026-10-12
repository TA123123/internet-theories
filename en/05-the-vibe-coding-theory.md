# The Vibe Coding Theory (Vibe Coding理论)

> Use AI to assist programming — ordinary people can build software, and ideas become reality.
> Chinese: [Vibe Coding理论](../zh/05-Vibe%20Coding理论.md)

## One-liner

Forget the code exists — describe in plain language what you want; the AI writes and debugs it, and you just see if it runs.

## Where the concept comes from

- Coined by **Andrej Karpathy** (OpenAI co-founder, former head of AI at Tesla) in February 2025.
- Named the **Collins Dictionary Word of the Year 2025** — the representative new programming paradigm of the AI era.

## Core claims

1. **Natural language is code**: state requirements in plain speech; the model generates and debugs.
2. **"See nothing" development**: Karpathy's original provocation was not reading the code line by line — only reacting to whether it works.
3. **Democratized development**: product managers, designers, operators who don't know syntax can still ship working software from their ideas.
4. **From "writing code" to "stating intent and judging results"**: human value shifts to taste, architectural sense and judgment about output.

## Practical path

- State requirements clearly: more context → better output (give examples, constraints, boundaries).
- Small steps: change one thing at a time, run, then continue.
- Be able to read what's generated: at minimum, judge right from wrong — especially for keys, payments, deletes.
- Security first: AI-generated code can contain vulnerabilities or pull in malicious dependencies; review before shipping.

## Caveats

- Great for prototypes, personal tools, scripts and landing pages; production systems still need engineering (testing, security, maintainability).
- "Everyone can build software" is exaggerated: code generation got cheap, but knowing *what* to build got more valuable.
- Maintenance debt: a pile of code you don't understand comes due later — and you pay it.

## Sources

- Juejin: "Vibe Coding from beginner to practice, 2026"
- CSDN: "Vibe Coding explained: Karpathy's concept, principles"
- Baidu Baike: entry "氛围编程" (vibe coding)
