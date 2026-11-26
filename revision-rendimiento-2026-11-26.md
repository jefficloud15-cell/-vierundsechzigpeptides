# Performance / accessibility — phase 1, 2026-11-26

Baseline supplied by site owner: mobile home 76 performance, 82 accessibility, 100 best practices, 85 SEO, LCP 5.6 s, FCP 2.1 s, TBT 90 ms, CLS 0.006. Journal mobile 91, desktop 99; mobile LCP 3.5 s.

Changes are intentionally limited to two HTML pages: mobile intro timer (520 ms to begin fade, 240 ms fade, CSS fallback), mobile hero no longer hidden by loading class, reduced-motion skip, main landmark, 16 existing in-page navigation links made real fragment links, six controls/link/dialog names plus five mobile buttons, improved legal notice contrast. Journal pulse and progress animation use transforms/opacity; lazy news images marked low priority, minor contrast adjustment. Desktop home intro behavior remains unchanged for normal-motion users.

Not addressed: responsive image variants, local font hosting, cache/security headers, analytics timing, all generic catalog link labels, dynamic dialog focus behavior and all contrast issues. No DNS or tracking changes. No product data, payment or cart logic intentionally changed. No live/browser/Lighthouse validation yet. The report's LCP subparts total 2.63s, not 5.6s; causal attribution requires a repeat trace. Test mobile nav, language toggle, dialogs, cart, news carousel, reduced motion and desktop before publication; rerun Lighthouse after deployment.
