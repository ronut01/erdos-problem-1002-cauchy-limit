# A Cauchy Limit for a Sawtooth Sum

This repository contains a proposed resolution of [Erdos Problem #1002](https://www.erdosproblems.com/1002).

For

\[
S_n(\alpha)=\sum_{k=1}^n\left(\frac12-\{k\alpha\}\right),
\]

the manuscript proves, for uniformly distributed \(\alpha\in(0,1)\),

\[
\frac{S_n(\alpha)}{\log n}
\Longrightarrow
\operatorname{Cauchy}\left(0,\frac1{2\pi}\right).
\]

The limiting distribution function is therefore

\[
g(c)=\frac12+\frac1\pi\arctan(2\pi c).
\]

## Files

- `erdos1002_cauchy_limit.pdf` — compiled manuscript
- `erdos1002_cauchy_limit.tex` — LaTeX source

## AI-use disclosure

The proposed answer was first obtained in a one-shot ChatGPT response using OpenAI GPT-5.6-sol Pro. The proof was subsequently developed and gaps were addressed through iterative prompting of that model. OpenAI Codex (GPT-5.6-sol) was used to assemble, edit, compile, and perform automated consistency audits of the manuscript.
