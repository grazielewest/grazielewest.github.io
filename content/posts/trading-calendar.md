——-
title: “📅 Trading Calendar - January 2024”
date: 2024-01-27
draft: false
——-

<style>
.calendar-grid {
    display: grid;
    grid-template-columns: repeat(7, 1fr);
    gap: 6px;
    max-width: 700px;
    margin: 0 auto;
}
.calendar-header {
    font-weight: 700;
    text-align: center;
    padding: 8px;
    background: #1e293b;
    color: white;
    border-radius: 6px;
}
.calendar-day {
    text-align: center;
    padding: 12px 0;
    border-radius: 8px;
    background: #f1f5f9;
    font-size: 0.9rem;
    transition: transform 0.2s;
}
.calendar-day:hover {
    transform: scale(1.05);
}
.day-number {
    font-weight: 700;
    font-size: 1.1rem;
}
.profit {
    background: #dcfce7;
    color: #16a34a;
}
.loss {
    background: #fee2e2;
    color: #dc2626;
}
.break-even {
    background: #fef9c3;
    color: #ca8a04;
}
.no-trade {
    background: #f1f5f9;
    color: #94a3b8;
}
.legend {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 1.5rem;
    font-size: 0.85rem;
}
.legend-item {
    display: flex;
    align-items: center;
    gap: 6px;
}
.legend-color {
    width: 16px;
    height: 16px;
    border-radius: 4px;
}
</style>

<div class=“legend”>
    <div class=“legend-item”><span class=“legend-color” style=“background: #dcfce7;”></span> Profit</div>
    <div class=“legend-item”><span class=“legend-color” style=“background: #fee2e2;”></span> Loss</div>
    <div class=“legend-item”><span class=“legend-color” style=“background: #fef9c3;”></span> Break-even</div>
    <div class=“legend-item”><span class=“legend-color” style=“background: #f1f5f9;”></span> No Trade</div>
</div>

<div class=“calendar-grid”>
    <!— HEADERS —>
    <div class=“calendar-header”>Mon</div>
    <div class=“calendar-header”>Tue</div>
    <div class=“calendar-header”>Wed</div>
    <div class=“calendar-header”>Thu</div>
    <div class=“calendar-header”>Fri</div>
    <div class=“calendar-header”>Sat</div>
    <div class=“calendar-header”>Sun</div>

    <!— DAYS - January 2024 —>
    <!— Week 1 —>
    <div class=“calendar-day no-trade”><span class=“day-number”>1</span><br>No trade</div>
    <div class=“calendar-day profit”><span class=“day-number”>2</span><br>+$50</div>
    <div class=“calendar-day loss”><span class=“day-number”>3</span><br>-$30</div>
    <div class=“calendar-day break-even”><span class=“day-number”>4</span><br>$0</div>
    <div class=“calendar-day profit”><span class=“day-number”>5</span><br>+$75</div>
    <div class=“calendar-day profit”><span class=“day-number”>6</span><br>+$120</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>7</span><br>No trade</div>

    <!— Week 2 —>
    <div class=“calendar-day loss”><span class=“day-number”>8</span><br>-$45</div>
    <div class=“calendar-day profit”><span class=“day-number”>9</span><br>+$60</div>
    <div class=“calendar-day break-even”><span class=“day-number”>10</span><br>$0</div>
    <div class=“calendar-day profit”><span class=“day-number”>11</span><br>+$90</div>
    <div class=“calendar-day profit”><span class=“day-number”>12</span><br>+$150</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>13</span><br>No trade</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>14</span><br>No trade</div>

    <!— Week 3 —>
    <div class=“calendar-day loss”><span class=“day-number”>15</span><br>-$20</div>
    <div class=“calendar-day profit”><span class=“day-number”>16</span><br>+$110</div>
    <div class=“calendar-day profit”><span class=“day-number”>17</span><br>+$80</div>
    <div class=“calendar-day profit”><span class=“day-number”>18</span><br>+$45</div>
    <div class=“calendar-day break-even”><span class=“day-number”>19</span><br>$0</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>20</span><br>No trade</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>21</span><br>No trade</div>

    <!— Week 4 —>
    <div class=“calendar-day profit”><span class=“day-number”>22</span><br>+$200</div>
    <div class=“calendar-day profit”><span class=“day-number”>23</span><br>+$35</div>
    <div class=“calendar-day loss”><span class=“day-number”>24</span><br>-$60</div>
    <div class=“calendar-day profit”><span class=“day-number”>25</span><br>+$95</div>
    <div class=“calendar-day profit”><span class=“day-number”>26</span><br>+$140</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>27</span><br>No trade</div>
    <div class=“calendar-day no-trade”><span class=“day-number”>28</span><br>No trade</div>

    <!— Week 5 —>
    <div class=“calendar-day profit”><span class=“day-number”>29</span><br>+$70</div>
    <div class=“calendar-day profit”><span class=“day-number”>30</span><br>+$110</div>
    <div class=“calendar-day profit”><span class=“day-number”>31</span><br>+$90</div>
</div>

## 📊 Monthly Summary

| Metric | Value |
|———|-——|
| **Total Trades** | 20 |
| **Winning Trades** | 13 |
| **Losing Trades** | 4 |
| **Break-even** | 3 |
| **Win Rate** | 65% |
| **Total P&L** | **+$1,335** |
| **Best Day** | $200 (Jan 22) |
| **Worst Day** | -$60 (Jan 24) |