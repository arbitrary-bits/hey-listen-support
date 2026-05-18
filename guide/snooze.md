# Snooze

Snooze an alert to be reminded again later — closer to when your event actually starts.

---

## Snooze Options

When an alert appears, you have several snooze choices:

| Button | What it does |
|---|---|
| **Snooze 1 min** | Dismiss the alert and re-show it in 1 minute |
| **Snooze 5 min** | Dismiss and re-show in 5 minutes |
| **Snooze 10 min** | Dismiss and re-show in 10 minutes |
| **Snooze until N min before** | Dismiss and re-show at your configured lead time before the event |
| **Snooze until start** | Dismiss and re-show exactly when the event begins |

> **Screenshot placeholder:** Alert showing all snooze buttons including "Snooze until 1 min before" and "Snooze until start"

**Snooze until N min before** only appears when there's actually time for it to be useful — it won't show if the snooze would fire after the event ends.

**Snooze until start** is always visible, but becomes disabled once the event has started.

---

## Configuring "Snooze Until Before"

The **N** in "Snooze until N min before" is configurable. Go to **Settings → Alerts** and adjust the **"Snooze until before" minutes** field.

> **Screenshot placeholder:** Alerts tab showing the "Snooze until before minutes" field with stepper

For example, if you set this to 2 minutes, the button will read "Snooze until 2 min before", and snoozing will re-show the alert 2 minutes before the event starts — giving you one final heads-up right before go time.

---

## How Snooze Works

When you snooze, Hey Listen schedules the alert to re-fire at the calculated time. If that time passes while your Mac is asleep, the alert fires as soon as you wake up — as long as the event hasn't ended yet.

Each snooze is tracked per event, so snoozed alerts don't interfere with alerts for other events happening around the same time.

---

← [Guide Index](README.md)
