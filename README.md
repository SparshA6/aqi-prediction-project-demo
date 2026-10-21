# AQI Prediction - public historical dashboard

Open `index.html` in a browser or place this directory on a static web host. It needs no server, account, or API key. It embeds saved 2024 same-day, 2025 GRU next-day, and January-September 2026 weather-model backtests.

Visitors can choose a city and station, change dates, toggle chart series, inspect daily values, compare paired historical models, search and sort stations, and export selected rows. The embedded values are fixed at the time this package was built. They are not live AQI readings or a score for the reserved October-December 2026 prospective study.

Ground observations are derived from CPCB station exports and processed into UTC daily targets. The methodology and results PDFs are included for context and limitations. The 2024, 2025, and 2026 comparisons have different test cohorts; do not rank their scores as one matched test.

Custom station and city forecasts require Python and the frozen model. Download `AQI_Local_Demo.zip` from the page for those functions. City chart values are averages of available station observations or predictions, not official city AQI.

For static hosting, upload `index.html`, `AQI_Local_Demo.zip`, and both included PDFs together. Do not upload development data, the raw CPCB files, credentials, or the training environment.
