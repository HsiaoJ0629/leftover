# Leftover

**Bills, savings & guilt-free money.**

Leftover is a simple budget calculator. Enter your take-home pay and your regular bills, and it shows what's left over. It also shows how much to keep for emergencies, how fast you'll reach a savings goal, and how much you can spend each day without guilt.

👉 **Try it:** https://hsiaoj0629.github.io/leftover/

## Features

- **Left to spend:** your pay minus your bills, shown per day, week, fortnight, month or year.
- **Regular bills:** add bills at any frequency (weekly rent, quarterly power, yearly rego). Quick-add buttons cover common bills, and a colour bar shows where your money goes by category.
- **Income for a comfy life:** based on your bills, the take-home pay that puts you in each of four zones: **Short** (bills are more than your pay), **Tight** (bills are 70–100% of pay), **Getting by** (50–70%) or **Comfy** (the 50/30/20 rule: bills take no more than half your pay). See where you sit, what it would take to be comfy, and what that is as a before-tax salary (Australian tax rates).
- **Emergency fund:** how much you need to cover 3 or 6 months of bills if you lose your job. One click makes it your savings goal.
- **Savings goal:** set a goal and choose how much of your leftover to save. You see how long it will take, the target date, and the fastest it could happen.
- **Guilt-free spending:** after bills and savings, how much you can spend per day. Type in a purchase (like a $10 snack) and see whether it fits. Based on Ramit Sethi's *Conscious Spending Plan*.
- **Example budget:** load sample numbers to see how it all works.
- **Print:** a clean, printer-friendly summary of your budget (or save it as a PDF).
- **Export & import:** copy your budget as JSON text (or download it as a file) and import it on another device.

## Privacy

Everything runs in your browser. Your numbers are saved only in your browser's local storage and are never sent anywhere. To move your budget to another device, use **Export** and **Import**.

## Run it locally

There's nothing to install. It's a single HTML file:

```bash
git clone https://github.com/HsiaoJ0629/leftover.git
cd leftover
# open index.html in your browser
```

## Deploy with GitHub Pages

1. Go to **Settings → Pages** in this repo.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute or so, the site is live at `https://<your-username>.github.io/leftover/`.

## Disclaimer

Leftover gives estimates and rules of thumb, not financial advice.
