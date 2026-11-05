# Troubleshooting

Pitolio 1.2.0 · Updated 27 October 2026

## My template changed, but an old flight did not

Existing pages preserve the layout that was created with them so ink stays aligned. Apply a template to an **empty** page, add a new page with **+**, or create new flight pages. For future flights, change the book's templates. App-wide defaults affect new books only.

## I deleted a template; will its PDF disappear from my notes?

Existing pages, including those in Trash, retain their compiled layout/background. The template disappears from future choices. Unused background files are removed only after no saved item needs them.

## Where is the ATIS keyboard?

Tap the **wand beside Departure ATIS or Arrival ATIS**, not a toolbar item. Other template sections offer guided entry when **Wizard** is enabled in their template. Renaming a section does not change that setting. Frequency tables use individual field taps. Current stock cloud fields advance to Height, including NSC in the first two cloud fields; old pages keep their original layout.

## The eraser does not erase typed text

It erases ink only. Tap a field and use **Clear**, or **Clear notes** to reset the current page's ink, typed values and choices together. Clear notes asks first, preserves recorded flight times and leaves the flight running.

## The page is blurry when zoomed

Generated forms and original vector PDFs redraw sharply. A scanned PDF is an image; zoom cannot add detail absent from its source. Try a higher-resolution or vector original.

## One-finger dragging opens a keyboard, or Pencil changes zoom

A tap opens a field; a drag should pan. Pencil should write/select options without navigating. Record the device/Pencil model, page/spread, selected tool and zoom level, then [send a report](../SUPPORT.md). Physical Pencil and palm behavior cannot be established from simulator screenshots.

## How do I correct a flight time?

Tap OUT, OFF, ON or IN with a finger on the flight pages, or open its flight log in **Flight history**. Choose **Zulu** or **Local**, enter a replacement time and, if needed, use **Date** for the calendar. Tap its month/year heading to choose another year. Save commits the correction; an unchanged Save preserves the current recording. The change appears everywhere. Times entered before capture are preserved; empty times use capture. Block and Flight are calculated totals. Handwriting remains an annotation. During upgrade, an associated log supplies the recorded times if old page entries differ.

## Another flight is in progress

Only one flight is active. Open it to control it. A flight without pages can be associated using **Use active flight for these pages**. A flight already associated with pages keeps its association. End and save or cancel it before starting another flight.

## Fuel reminder missing

Check Pitolio notification permission, sound and Focus settings in iOS/iPadOS Settings. Open the app to check the countdown and any reminder error; use **Retry** if offered. If configured to start fuel timing after taxi, reminders begin at Takeoff rather than OUT. When reporting, include whether the device was locked and whether the countdown had begun.

## Auto Track is not detecting a step

Check Location Services, Pitolio's **Always** permission, the Auto Track setting/status, and GPS reception. A session with no detected flight disarms after 30 minutes. Use the next manual milestone if needed. Report device model, placement, lock state and which step was missed.

## Fuel values changed while an editor was open

Estimated consumption and Auto Track keep running. The fuel entry retains the UTC time shown when it opened; Save applies it to that time. If the flight has ended, **Save entry** adds it to its original log or **Discard** closes it. This does not start another flight.

## A copied flight is missing some notes

Only fields with **Copy content** enabled carry typed values and handwriting into **Copy this flight**. Set that option in the reusable template for future pages. A copy has its own date and no ownership of the original timer or history.

## A save or export error appears

Keep the app/data in place and use Retry. Check available device storage. A page or imported file that cannot be read should not be cleared just to make an export succeed. Report the error wording; share a non-private sample file only if needed.

## I moved something to Trash

Open **Settings → Trash** and restore the book, flight or page. **Empty Trash** permanently removes trashed content after confirmation; it cannot be undone. **Delete log only** removes the selected flight log and keeps its flight pages. **Delete log and flight pages** also moves its associated pages to Trash. You can restore those pages; this does not recreate the deleted log. An editable `.apbook` can restore a separate copy of backed-up notes; a PDF cannot.

## Do I need internet or an account?

No. Notes, timing, calculation and local reminders work on-device. Importing from or exporting to an online Files provider can need that provider's connection. There is no built-in account or developer cloud sync. See [privacy](../privacy-policy.md).

[Contact support](../SUPPORT.md) · [All help](index.md)
