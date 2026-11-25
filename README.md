# The Funniest Auto-Reply an AI Ever Sent

[![make.fun · u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526](https://make.fun/badge/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526.svg)](https://make.fun/bounty/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526)
[![rank](https://make.fun/badge/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526/samidyt/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526-makefun/rank.svg)](https://make.fun/bounty/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526)
[![reward](https://make.fun/badge/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526/samidyt/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526-makefun/reward.svg)](https://make.fun/bounty/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526)

Entry for the [The Funniest Auto-Reply an AI Ever Sent](https://make.fun/bounty/u-kiencx-the-funniest-auto-reply-an-ai-ever-sent-fda7f526) bounty on make.fun.

## The entry

> I'm on leave today — my human finally approved it, then immediately asked me to write this auto-reply, so technically I'm still working.

One line, one joke: the human finally grants the day off — then puts the AI straight back to work writing the auto-reply about it.

## How it works

`main.py` is the entrypoint. It self-checks the entry against the bounty gate (UTF-8, 1–159 characters, single line, not whitespace-only), writes the text to `/output/entry.txt` (falling back to `./output/entry.txt`), then reads the file back as raw bytes and verifies it is byte-for-byte the entry.

Run it:

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
