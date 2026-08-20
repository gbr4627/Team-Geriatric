# MarketPlay mobile prototype

Open `index.html` in any modern browser. The prototype is self-contained and does not need a build step or network connection.

Key journeys:

- Complete two-step onboarding or preview as a guest.
- Scroll six full-height demonstration news cards.
- Open the lead interest-rates story for the complete six-card explainer.
- From the final story card, open Ask MarketPlay, the two-decision activity, or the historical simulation.
- Use all five bottom-navigation destinations; save stories and open the Pro upgrade from Profile.
- Open Explore → Market archive to browse every stored day since launch, filter stories versus simulations, and reopen any item.
- Run the investment simulation from the archive or the final card of the lead story. Each decision supports three suggested choices or a written custom strategy.
- Choose between the quick decision scenario and a simplified stock-trading demo. The trading demo adds market metrics, position sizing and risk controls as the user’s knowledge level advances.
- Open the interactive market view from Explore or the lead story. Switch instruments, watch simulated live ticks and tap numbered news markers to see the price at each event and the evidenced explanation for the move.
- Review loading, error and offline states in Profile → Prototype states. They are also available from the browser console with `MarketPlay.showState('loading')`, `MarketPlay.showState('error')`, or `MarketPlay.showState('offline')`.

All news, market figures, sources and scenarios are explicitly demonstration content. The product includes educational—not financial—guidance.
