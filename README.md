# Repsol Contractor Invoice Resolution demos

Self-contained demo pages for embedding in a Celonis Studio view (iframe component).

| # | Page | URL |
|---|---|---|
| 01 | Apollo builds the Context Model | https://smiqueleti.github.io/CCM/repsol-apollo.html |
| 02 | How the agent consumes the Context Model | https://smiqueleti.github.io/CCM/repsol-agent-context.html |
| 03 | Microsoft Copilot Studio agent | https://smiqueleti.github.io/CCM/repsol-copilot-studio.html |
| 04 | Decision Deep Dive · Resolution Agent DEC-17928 | https://smiqueleti.github.io/CCM/decision-deep-dive.html |

Optional URL parameters:

- `repsol-apollo.html?static=1` opens on the finished model; `?auto=1` plays on its own.
- `repsol-agent-context.html?static=1` opens on the final state; `?auto=1` plays on its own.
- `repsol-copilot-studio.html?tab=Test` opens a specific tab (`Overview`, `Tools`, `Instructions`, `Test`, `Evaluation`).
- `decision-deep-dive.html?span=model` opens with a span selected (`agent`, `retrieve`, `liability`, `policy`, `model`, `action`).

All data, tool calls and results are predefined and fictitious. Nothing connects to Celonis, SAP or Microsoft services.
The pages are recreations for demonstration; product names and logos belong to their owners.

## MC Fresh Supply Chain demos (synthetic)

Three connected pages for a fresh supply chain scenario.
Everything is synthetic and simulated.
The first two pages are Celonis views, and the third imitates an agent workspace.

| # | Page | URL |
|---|---|---|
| 01 | Apollo builds the Context Model | https://smiqueleti.github.io/CCM/sonae-apollo.html |
| 02 | How the agent consumes the Context Model | https://smiqueleti.github.io/CCM/sonae-agent-context.html |
| 03 | Agent workspace: decide and act | https://smiqueleti.github.io/CCM/sonae-copilot-studio.html |

Optional URL parameters:

- `sonae-apollo.html?static=1` opens the finished model, `?auto=1` plays on its own, and `?scenario=stockout` opens with the strawberry stockout case highlighted.
- `sonae-agent-context.html?scenario=stockout|waste` selects the validated stockout or the illustrative expiry what-if, and `?static=1` or `?auto=1` work as above.
- `sonae-copilot-studio.html?tab=Test` opens a tab (`Overview`, `Tools`, `Instructions`, `Test`, `Evaluation`), and `&q=q1` to `&q=q6` asks a predefined question.


## TIM Brasil NOI agent demo (synthetic)

Microsoft Copilot Studio look-alike for the Network Operations recurrence and context agent.
The data is demonstrative and simulated; none of the numbers are real TIM results.
The agent is read-only and runs no action in operational systems.

| Page | URL |
|---|---|
| Copilot Studio agent (pt-BR) | https://smiqueleti.github.io/CCM/tim-copilot-studio.html |

Optional URL parameters:

- `tim-copilot-studio.html?tab=Test` opens a tab (`Overview`, `Tools`, `Instructions`, `Test`, `Evaluation`), and `&demo=1` asks the first question automatically.
