# Free AI Pool — verified daily brief (2026-11-16)

_Generated 2026-11-16T00:18:49.336023+00:00 · schema 1.0 · free-tier intelligence, liveness-verified_

## Today in one line
**14 models answer for $0 right now** across 6/6 live catalogs (1715 models scanned). 0 newly free, 0 gone since the last run.

## Usable now (verified by live probe)

| Model | Provider | Verdict | Evidence |
|---|---|---|---|
| `baidu/ernie-5.5-flash-preview:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `cohere/north-mini-code:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `dots-studio/dots-3-note-preview:free` | OpenRouter | **WORKING** | live turn ok, reply='\n\nOK' |
| `google/lyria-3-clip-preview` | OpenRouter | **WORKING** | live turn ok, reply='[4.0:8.0] OK\n[16.0:2' |
| `google/lyria-3-pro-preview` | OpenRouter | **REACHABLE** | HTTP 200, empty content (reasoning/silent model) |
| `inclusionai/ling-3.2-flash:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `liquid/lfm-3-1.7b:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `nvidia/nemotron-3-ultra-550b-a55b:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `nvidia/nemotron-3.5-lightning:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `nvidia/nemotron-3.5-super-vl:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `openrouter/free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `particle-ai/particle-1:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |
| `recursive/flint-v1.0:free` | OpenRouter | **WORKING** | live turn ok, reply='OK' |

## What to do about it

- NEEDS_SIGNUP: free signup, no card needed -> instant access to 22 free models
- NEEDS_KEY: add NOUS_API_KEY / APINEX_API_KEY to hermes .env -> 3 catalog-confirmed free models
- BLOCKED: listed free but refused from our egress (1) - retry, don't assume dead
- AT_CAPACITY: at capacity right now (2) - free but queued/429

## Free but at capacity right now

- `google/gemma-4-26b-a4b-it:free` (OpenRouter) — HTTP 429 (rate/capacity, not dead)
- `google/gemma-4-31b-it:free` (OpenRouter) — HTTP 429 (rate/capacity, not dead)

## Listed free but blocked from our network

- `thinkingmachines/inkling-2-small:free` (OpenRouter) — HTTP 403 forbidden (route/region/bot gate)

## The pool over time (free models by day)

| date | free rows | usable (verified) |
|---|---|---|
| 2026-11-15 | 53 | 13 |
| 2026-11-15 | 53 | 13 |

## Method (why this is not just a listings site)

- catalog pricing (zeros / :free suffix / synthesized-free flag) cross-checked against a live 400-token chat probe; tiers: WORKING (text back) / REACHABLE (200 but silent) / AT_CAPACITY (429) / BLOCKED (403) / DEAD / NEEDS_KEY / NEEDS_SIGNUP
- an empty reply is not a success: reasoning models burn the token budget silently, so they grade REACHABLE, not WORKING
- Sources: https://www.llmperks.com/, https://aifree.dev/, https://raw.githubusercontent.com/peter123023/awesome-free-llm-api/main/README.md, https://raw.githubusercontent.com/rockbenben/free-llm-intel/main/README.md, https://openrouter.ai/api/v1/models, https://inference-api.nousresearch.com/v1/models …

Machine feed: `feed.json` (schema 1.0) · daily entries: `feed.jsonl` · full ledger: `ledger.jsonl`
