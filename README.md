### Hi, I'm Marco 👋

Software engineering leader — AI-assisted engineering workflows, cloud
infrastructure, data platforms, and high-throughput systems. Go · Python ·
PHP, building since 2002 and still close to the code. Built self-healing
infrastructure because “see you at 3 a.m.” isn’t an engineering strategy.

```go
package marco

import "errors"

// Motivation — the three dependencies I refuse to run without.
type Motivation struct {
	Autonomy bool
	Mastery  bool
	Purpose  bool
}

func (m Motivation) HealthCheck() error {
	switch {
	case !m.Autonomy:
		return errors.New("feeling controlled")
	case !m.Mastery:
		return errors.New("feeling stagnant")
	case !m.Purpose:
		return errors.New("feeling pointless")
	default:
		return nil // all systems go
	}
}
```

> "The insane repeat the same act hoping for change —
> the genius repeats with purpose to create it."

- 🖥️ [marco-montesines.github.io](https://marco-montesines.github.io/) — an
  OS with exactly one user: boot screen, Spotlight, draggable windows, a
  working terminal (try `exit`), music, and apps named in Tagalog — Sulat
  ✍️, Hanap 🔍, Likha 💻, Harapan 🎥. A brief overview of me lives inside.
- 🔧 [haveibeenpwned](https://github.com/marco-montesines/haveibeenpwned) — unofficial Go client for the HIBP API v3
- 📈 day job: the pipes behind 20+ financial-media portals — ~2B documents
  searched, ~1.64B rows analyzed, 99.9% uptime (the remaining 0.1% still
  haunts me)
- 🤖 AI writes my boilerplate — the interesting problems remain loyal to me
- 🔍 taught AI to review my code — it learned my standards, not my shortcuts
- 🔗 [LinkedIn](https://www.linkedin.com/in/mamontesines) · [GitLab](https://gitlab.com/marco.montesines)
- ♻️ current status: `for { improve() }`
