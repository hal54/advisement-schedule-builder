# Advisement Schedule Builder

Turn a spreadsheet of faculty advising hours into a student-friendly schedule you can paste into an OpenLab (WordPress) Custom HTML block, or host as its own web page.

**Open the builder:** https://hal54.github.io/advisement-schedule-builder/

Made for the Media Arts and Technology Department at BMCC (CUNY) and shared for any department to use.

## How it works

1. **Download the workbook template.** It has two sheets:
   - **Faculty:** one row per advisor, with email, programs, usual room, Zoom link, booking link and notes entered once.
   - **Slots:** one row per advising slot (professor, day, start, end, format). Fill in Room, Zoom Link, Booking Link or Notes only when a slot differs from the advisor's usual details.
2. **Fill it in** with Excel or Google Sheets, then drop the workbook back into the builder. Two CSVs (faculty and slots) or a single combined CSV also work.
3. **Check and edit.** The builder lists anything to fix, and the Edit data tables let you change any value, add or remove slots and advisors, and sort by day and time, first name or last name.
4. **Fill in Page details:** department, semester, programs, accent colour, help text and professor order.
5. **Copy the embed code.**
   - **Static version:** plain HTML with inline styles. Paste it into an OpenLab Custom HTML block; WordPress keeps it intact.
   - **Interactive version:** search, day, format and program filters and a live Now badge. WordPress multisite networks such as OpenLab strip scripts, so host it as its own page (for example on GitHub Pages) and link to it.

Rooms appear only on in-person slots, and Zoom and booking links only on online slots.

## Privacy

Everything runs in your browser. Files you load are never uploaded; your work is saved only in your own browser's storage.

## Files

- `index.html`: the whole builder in one self-contained file.
