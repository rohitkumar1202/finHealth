# **PFIP V2.6 — README / User Guide**

**Personal Finance & Investment Platform**\
**Version:** 2.6\
**Platform type:** Offline-first, single-file household finance application

## **1. Introduction**

PFIP (Personal Finance & Investment Platform) is a personal household finance management and investment planning application designed to bring financial records, investment tracking, retirement planning and wealth management into one place.

The application runs directly in a modern web browser using a single HTML file. It does not require a user account or subscription to use its core household finance features.

PFIP helps users:

- Track household income and expenses.
- Monitor assets, liabilities and net worth.
- Manage investment holdings and transactions.
- Estimate investment growth and retirement withdrawals.
- Plan for FIRE (Financial Independence, Retire Early).
- Review insurance and financial protection.
- Organize estate and legacy information.
- Track financial progress through dated snapshots.
- Maintain encrypted copies of important documents.
- Review market information and financial news.

PFIP is intended for personal financial organization, analysis and planning. It is not a bank, brokerage, tax filing service or professional financial advisory service.

## **2. Installation and Getting Started**

### **System requirements**

- Windows, macOS or Linux.
- A modern browser such as Google Chrome, Microsoft Edge, Firefox or Safari.
- JavaScript enabled.
- Internet connection for online market data and financial news features.

### **How to open PFIP**

1. Save the file `Dashboard.html` to your computer.
2. Locate the downloaded file.
3. Double-click the HTML file or right-click and select your preferred browser.
4. PFIP will open in your browser.
5. Use the navigation menu to access the different financial modules.

No installation wizard or account registration is required.

### **Important storage information**

PFIP stores ordinary household financial records in your browser's local storage.

This means:

- Your records are associated with the browser and browser profile you use.
- Opening PFIP in another browser or on another computer does not automatically transfer your data.
- Clearing browser data may delete your PFIP records.
- You should regularly export backups.

**Always maintain a separate backup of your financial records.**

## **3. Platform Modules**

PFIP V2.6 includes 13 main modules.

### **3.1 Financial Overview**

The Financial Overview is the main dashboard of PFIP.

It provides a consolidated view of your household financial position, including:

- Total assets.
- Total liabilities.
- Net worth.
- Investable assets.
- Income and expenses.
- Savings rate.
- Financial Health Score.
- Asset allocation.
- Financial progress over time.

The dashboard also includes a welcome banner and visual summaries of your financial position.

Use this section regularly to review your household's overall financial health.

### **3.2 Income & Budget**

This module helps organize household income and budgeting.

Use it to record and monitor:

- Employment income.
- Spousal income.
- Business income.
- Rental income.
- Other income sources.
- Monthly and annual income.
- Household budget allocations.

The purpose is to understand how much money enters the household and how it is allocated.

### **3.3 Expense Manager**

The Expense Manager helps track household spending.

Use it to organize expenses into appropriate categories and review:

- Monthly expenses.
- Annual expenses.
- Essential expenses.
- Discretionary expenses.
- Recurring expenses.
- Spending patterns.

Regular expense tracking helps identify unnecessary spending and opportunities to increase savings.

### **3.4 Insurance & Protection**

This module maintains an overview of household insurance and protection policies.

You can organize information about:

- Life insurance.
- Health insurance.
- Critical illness insurance.
- Disability insurance.
- Home insurance.
- Auto insurance.
- Other protection policies.

Keep policy amounts, premiums, renewal dates and beneficiary information accurate.

PFIP is a record-keeping tool and does not independently determine whether your insurance coverage is sufficient.

### **3.5 Assets & Net Worth**

This module provides a household balance-sheet view.

Record assets such as:

- Bank balances.
- Cash.
- TFSA investments.
- RRSP investments.
- FHSA investments.
- Non-registered investments.
- Real estate.
- Vehicles.
- Other valuable assets.

You can also record liabilities such as:

- Mortgage balances.
- Personal loans.
- Credit card balances.
- Other outstanding debts.

Your net worth is calculated from the recorded assets and liabilities.

Keep valuations updated to maintain a meaningful financial picture.

### **3.6 Investment Centre**

The Investment Centre is designed to track investment holdings and investment transactions.

It supports transaction types including:

- Buy.
- Sell.
- Contribution.
- Withdrawal.
- Distribution.
- Fee.
- Internal transfer.

The module includes investment tracking and analytical calculations such as:

- Portfolio allocation.
- Average-cost-based realized gain estimates.
- XIRR estimates.
- Modified Dietz-style return approximation.
- Valuation snapshots.
- Investment transaction history.

Use the transaction ledger consistently. Incorrect dates, missing transactions, duplicate records or inaccurate cash flows can affect calculated returns.

Investment calculations should be reconciled against official brokerage statements.

### **3.7 Investment Simulator**

The Investment Simulator in V2.6 provides three planning modes.

#### **A. SIP — Systematic Investment Plan**

Use SIP mode to estimate the future value of regular investments.

Inputs include:

- Initial investment.
- Monthly contribution.
- Expected annual return.
- Investment duration.
- Inflation assumption.

Results include:

- Projected portfolio value.
- Total amount invested.
- Estimated investment growth.
- Inflation-adjusted future value.
- Year-by-year projection.

SIP mode helps compare different monthly investment amounts and investment periods.

#### **B. SWP — Systematic Withdrawal Plan**

Use SWP mode to estimate how a portfolio may support regular withdrawals during retirement.

Inputs include:

- Starting investment corpus.
- Monthly withdrawal.
- Expected annual return.
- Withdrawal period.
- Inflation assumption.
- Annual withdrawal increase.

Results include:

- Projected ending corpus.
- Total withdrawals.
- Inflation-adjusted value.
- Estimated corpus depletion timing.
- Year-by-year projection.

This helps evaluate whether a retirement corpus may support a planned withdrawal amount over a selected period.

#### **C. Three-Bucket Retirement Strategy**

The three-bucket model divides retirement savings into three categories.

**Bucket 1 — Cash & Liquidity**

Designed to hold cash or highly liquid assets for near-term retirement expenses.

**Bucket 2 — Stability & Income**

Designed to hold relatively stable investments and income-producing assets.

**Bucket 3 — Long-Term Growth**

Designed to hold long-term growth investments intended to support future retirement needs.

Inputs include:

- Total retirement corpus.
- Monthly withdrawal.
- Retirement duration.
- Inflation or annual withdrawal increase.
- Allocation percentages for each bucket.
- Expected returns for each bucket.
- Replenishment frequency.

The simplified model pays withdrawals from Bucket 1 first, then Bucket 2, then Bucket 3. At the selected replenishment interval, it attempts to refill Bucket 1 from Bucket 2 and then Bucket 3.

The results include:

- Initial allocation to each bucket.
- Remaining balances.
- Total withdrawals.
- Inflation-adjusted withdrawal information.
- Estimated depletion status.
- Year-by-year projection.

**Important simulator limitations**

These simulations are based on assumptions, not guaranteed investment returns.

The three-bucket model is simplified and does not fully model:

- Market volatility.
- Sequence-of-returns risk.
- Investment taxes.
- Transaction fees.
- Changing interest rates.
- Real-world investment product restrictions.

Actual investment results may differ significantly from projected results. Always test conservative assumptions as well as optimistic ones.

### **3.8 Tax Planning**

The Tax Planning module provides simplified tax-planning estimates.

It can help users explore the potential impact of income and tax assumptions.

Tax calculations may vary depending on:

- Tax year.
- Country.
- Province or state.
- Residency status.
- Income type.
- Tax credits.
- Deductions.
- Other personal circumstances.

Tax rules change regularly. Verify all important calculations against official tax authority guidance or with a qualified tax professional.

### **3.9 FIRE & Retirement Planner**

The FIRE & Retirement Planner helps estimate progress toward financial independence and retirement.

FIRE means Financial Independence, Retire Early.

Use this module to explore:

- Retirement goals.
- Target retirement corpus.
- Current financial progress.
- Savings and investment assumptions.
- Expected retirement spending.
- Withdrawal-rate assumptions.
- Retirement timelines.

The planner helps compare different financial scenarios and understand how savings, investment returns, spending and inflation affect retirement goals.

The results are estimates, not guarantees of a particular retirement date.

### **3.10 Estate & Legacy Planner**

This module helps organize estate and legacy planning information.

It can be used to maintain records relating to:

- Assets.
- Beneficiaries.
- Estate planning.
- Family legacy information.
- Trust records.

This module does not create legally valid wills, trusts, powers of attorney or other legal documents.

Legal documents should be prepared or reviewed by qualified legal professionals under the applicable jurisdiction's laws.

### **3.11 Markets & Financial News**

This module provides access to market information, investment research and financial news.

Coverage includes selected financial instruments and economic information such as:

- Stocks.
- ETFs.
- Bond ETFs.
- Government bond yields.
- Fixed deposits and GICs.
- Commodities.
- Currencies.
- Central-bank rates.
- Volatility indicators.
- Macroeconomic indicators.
- Financial news.

Some information can be refreshed using external data providers.

Depending on the data source, an API key and internet connection may be required.

Market data status labels help distinguish between current provider responses, fallback observations, latest published data, manually entered data and unavailable information.

**Market data may be delayed, incomplete or unavailable.** Always verify important market information with the original provider before making investment decisions.

### **3.12 Encrypted Document Vault**

The Encrypted Document Vault provides a separate area for storing encrypted documents.

It uses AES-GCM encryption supported by the browser's Web Crypto functionality.

Typical documents may include:

- Insurance documents.
- Financial statements.
- Important certificates.
- Property documents.
- Estate-related records.
- Other sensitive household documents.

#### **How to use the vault**

1. Open Encrypted Document Vault.
2. Create a strong, unique passphrase.
3. Unlock the vault.
4. Select a document.
5. Use the encrypt-and-save option.
6. When required, unlock the vault and decrypt/download the document.
7. Lock the vault when finished.

#### **Important vault information**

- The vault is separate from the household JSON backup.
- Use the vault's own encrypted backup export feature.
- Keep your passphrase safe.
- If you lose the passphrase, PFIP cannot recover your encrypted documents.
- Keep an additional secure copy of important original documents.
- The vault supports files up to its configured 25 MB per-file limit.
- Browser support for Web Crypto and IndexedDB is required.

Do not share your vault passphrase with anyone.

### **3.13 Settings**

Settings contains application preferences and household data management features.

It includes:

- Household and profile assumptions.
- Financial planning settings.
- Snapshot management.
- Backup and restore options.
- Data privacy information.

Use Settings periodically to review your assumptions and protect your records.

## **4. Financial Snapshot Management**

A financial snapshot is a dated record of your household's financial position.

PFIP allows you to save snapshots from the main dashboard or Settings.

A snapshot may include:

- Net worth.
- Investable assets.
- Monthly income.
- Monthly expenses.
- Savings rate.
- Financial Health Score.
- Financial Health Score breakdown.
- FIRE progress.

### **Why save snapshots?**

Snapshots help you compare your financial progress over time.

For example:

- Compare net worth between months.
- Review changes in investable assets.
- Monitor savings-rate progress.
- Observe improvements in financial health.
- Track progress toward retirement goals.

### **Important**

Saving a snapshot is not the same as exporting a full backup.

A snapshot records a financial summary. It does not replace a complete household JSON backup.

Saving again on the same date updates the snapshot for that date.

## **5. Backup and Restore**

PFIP provides a full household JSON export and restore feature.

### **Exporting a backup**

1. Open Settings.
2. Locate Snapshot & Backup Management.
3. Select Export Full JSON Backup.
4. Save the downloaded JSON file in a secure location.
5. Keep a copy separate from your computer.

### **Restoring a backup**

1. Open PFIP.
2. Open Settings.
3. Select Restore JSON Backup.
4. Choose the previously exported JSON file.
5. Confirm the restore operation.

**Warning:** Restoring a backup replaces the current household PFIP data. Export your current records before restoring an older backup.

### **What is excluded from the household JSON backup?**

The household JSON backup does not include:

- Market-data module records and its separate saved market snapshots.
- Market API keys.
- Encrypted Document Vault files.

These features have separate storage and backup mechanisms.

If you use them, export their backups separately.

## **6. Data Privacy and Security**

PFIP is designed as an offline-first application for personal use.

However, users should understand the difference between ordinary browser storage and encrypted vault storage.

### **Ordinary household data**

Ordinary PFIP household records are stored in browser local storage.

They are not encrypted by PFIP.

### **Market API keys**

Market API keys are stored separately in browser storage and are not encrypted by PFIP.

Avoid using personal API keys on shared or public computers.

### **Encrypted Document Vault**

The document vault uses a separate encryption mechanism. This does not mean that the entire PFIP application or all household financial records are encrypted.

### **Recommended security practices**

- Use a password-protected computer account.
- Avoid public or shared computers.
- Keep your browser updated.
- Use a strong vault passphrase.
- Store backups securely.
- Do not share sensitive JSON backups.
- Lock the document vault after use.
- Maintain separate backups of important original documents.

## **7. Recommended Usage Routine**

For better financial record keeping, follow a regular schedule.

### **Weekly**

- Record new transactions.
- Update income and expenses.
- Review unusual spending.
- Check for missing investment transactions.

### **Monthly**

- Update account balances.
- Update investment valuations.
- Review asset allocation.
- Review net worth.
- Review savings rate.
- Save a financial snapshot.
- Export a household JSON backup.

### **Annually**

- Review insurance coverage.
- Review retirement assumptions.
- Review tax-planning assumptions.
- Review estate and legacy records.
- Reassess investment allocation.
- Review FIRE progress.
- Verify that your backups are accessible.

### **Before changing computers or browsers**

1. Export your household JSON backup.
2. Export the separate encrypted vault backup if used.
3. Export market data separately if needed.
4. Save all backup files in a secure location.
5. Open PFIP on the new device.
6. Restore the relevant data using the corresponding restore features.

## **8. Troubleshooting**

### **PFIP does not open**

- Confirm that the HTML file was downloaded completely.
- Open it using a modern browser.
- Ensure JavaScript is enabled.
- Try another modern browser if necessary.

### **My financial data is missing**

- Check that you are using the same browser and browser profile.
- Check whether browser data or local storage was cleared.
- Restore your latest household JSON backup if available.
- Remember that market data and vault files have separate backups.

### **Market data is not refreshing**

- Check your internet connection.
- Verify the relevant provider API key.
- Check provider availability and usage limits.
- Review the data status and observation date.
- Some information may only be available as the latest published release.

### **Encrypted vault does not unlock**

- Check that the passphrase is exactly correct.
- Confirm that you are using the same vault backup.
- Check browser support for Web Crypto and IndexedDB.
- Remember that PFIP cannot recover a lost passphrase.

### **Investment projections seem incorrect**

- Review the initial investment.
- Check monthly contributions or withdrawals.
- Confirm the investment duration.
- Verify expected return and inflation assumptions.
- Run alternative scenarios.
- Compare important figures with an independent calculator.

## **9. Important Disclaimer**

PFIP is provided as a personal financial organization and planning tool.

The application may use simplified formulas, assumptions and estimates. It does not guarantee investment performance or financial outcomes.

Nothing in PFIP should be considered individualized:

- Investment advice.
- Tax advice.
- Insurance advice.
- Legal advice.
- Estate-planning advice.

Users are responsible for verifying the accuracy of their entered information and the results generated by the application.

Consult qualified financial, tax, insurance or legal professionals before making important financial decisions.

## **10. PFIP V2.6 — What's New**

Version 2.6 includes the following improvements:

1. Integrated household finance platform with 13 modules.
2. Welcome banner positioned above the Financial Health Score.
3. More compact dashboard asset-allocation chart.
4. More compact Investment Centre portfolio distribution chart.
5. Expanded Investment Simulator with SIP mode.
6. Expanded Investment Simulator with SWP mode.
7. Three-Bucket Retirement Strategy simulator.
8. Settings snapshot management.
9. Recent financial snapshot history.
10. Clearer separation between financial snapshots and full JSON backups.
11. Improved backup and privacy guidance.
12. Existing investment, tax, FIRE, estate, markets and encrypted vault modules retained.

## **Final Recommendation**

PFIP works best when financial records are updated consistently and backups are maintained regularly.

Remember three important things:

- **Save snapshots** to track your financial progress.
- **Export household JSON backups** to protect your financial records.
- **Export encrypted vault backups separately** to protect your stored documents.

**PFIP V2.6 — One platform to organize, track and plan your household financial future.**
