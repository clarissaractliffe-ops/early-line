# Early Line: fabric passport and early sales signal

Working prototype with sample data. A single static page, no server; nothing is uploaded or stored.

Live: https://clarissaractliffe-ops.github.io/early-line/

- **Library**: leftover lots as Nona Source-style cards. Each lot's passport shows movements (where every metre went), quality tests and why a lot failed, restrictions and Nona Source eligibility, the FW27 styles it fits, how the quality sold, and the value recovered.
- **Pre-buy timing**: from your pre-buy calendar, Merch's drop calendar and PLM fabric lead times, which fabric has to go in which pre-buy to be in house for its store drop. Counts back from the in-store date (minus make-and-ship days, minus lead time), suggests the latest pre-buy that still works, checks the order export, and downloads as Excel.
- **Sales signal**: Power BI sell-through by base fabric moves each style's survival odds at pre-buy, and flags fast sellers with long lead times so undyed (RTD) fabric can be held for a reorder.
- **Nona Source export**: eligible lots in one CSV; restricted lots are kept out with the reason.
- **Value recovered**: reuse and resale against disposal, per lot, feeding the Savings report.
- **Clear sample data** (top of the page): removes every sample fabric, style, sales row, order line, lead time and survival rate, so the tool shows only the files you load in Data sources. Files you have already used stay. The choice is remembered in your browser; **Restore sample data** brings the sample back.

To make it permanent it needs hosting inside LVMH with sign-in, and read access to PLM, Power BI/ERP stock, sales and lab reports.
