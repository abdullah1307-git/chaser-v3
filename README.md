# Chaser v3: invoice tracker for freelancers

Freelancers keep track of unpaid invoices in spreadsheets, notes and folders. These go out of date when they get busy, and nothing tells them when an invoice is late. Chaser shows what needs action today and prepares reminders.

v3 adds changes from the maker fair tests (see testing notes):
1. **Light and dark theme.** Light is the default. Change it from the Theme button on Today or in Profile (Light, Dark or Match my device). New, softer colours.
2. **Profile page.** Name, business, email, default currency, default payment terms and theme. The name is used to sign reminders. Backup, sign out and clear data moved here.
3. **Undo many changes.** Recent activity lists payments and deleted invoices. Each can be undone on its own, in any order.
4. **Payment details.** Record amount, method (bank transfer, cash or cheque), date and a reference or cheque number. The invoice updates by itself, and each payment shows in its list.

Earlier versions: v1 (website) and v2 (prototype build) are in separate repos.

## Limits
Data is saved in the browser on that device only. Sign in is a demo. Reminders open your email app or copy the text.

## Run / deploy
Open `index.html`. Static site: deploy on Vercel with default settings (no build step).
