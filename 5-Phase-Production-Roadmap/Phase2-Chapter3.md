# CHAPTER 3 — CAPITAL STRUCTURE

## Chapter Introduction

With ownership and governance established, we now turn to the financial architecture of the institution. Capital structure is the design of the hierarchy, cost, flexibility, and resilience of financial claims on the institution.

Capital structure answers the fundamental questions:

- Who provides capital?
- In what form?
- At what cost?
- With what priority?
- With what control implications?
- With what downside protection?
- With what refinancing optionality?

Ownership defines **who owns**. Governance defines **who decides**. Capital structure defines **who gets paid first, at what cost, and under what conditions**.

The relationship between these three is critical. Ownership and governance determine who controls the institution. Capital structure determines who has claims on its value. If capital structure is misaligned with ownership and governance, the institution will face conflicts, financial distress, and potential failure.

This chapter provides the architecture for designing capital structure that is bankable, resilient, and aligned with institutional objectives. It addresses the full spectrum of capital considerations—from the equity-debt mix to seniority, covenants, refinancing, and liquidity.

### Why Capital Structure Matters

| Dimension | Why Capital Structure Matters |
|---|---|
| **Financial Viability** | Capital structure determines whether the institution can fund its operations and growth. |
| **Risk Allocation** | Capital structure allocates risk among different stakeholders. |
| **Cost of Capital** | Capital structure determines the institution's cost of capital. |
| **Control** | Capital structure determines who has control (equity holders vs. debt holders). |
| **Resilience** | Capital structure determines whether the institution can survive financial shocks. |
| **Bankability** | Institutional capital providers evaluate capital structure rigorously. |

### How This Chapter Is Organized

This chapter follows the standard MICOS-25 chapter template:

1. **Strategic Function:** Why capital structure exists and what risk it controls.
2. **Scope Boundary:** What capital structure governs and what it does not.
3. **Dependency Position:** How capital structure relates to other chapters.
4. **Failure Modes:** How capital structure can fail and how to prevent failure.
5. **Design Principles:** The non-negotiable rules of capital structure design.
6. **Structural Components:** The concrete elements of capital architecture.
7. **Architecture Patterns:** Proven configurations for different contexts.
8. **Capital Priority Matrix:** A tool for mapping claim priority.
9. **Implementation Sequence:** Step-by-step guidance for building capital structure.
10. **Stress Testing Framework:** How to test capital structure against shocks.
11. **Bankability & Institutional Test:** What capital providers look for.
12. **Red Flags:** Warning signs of capital structure weakness.
13. **Documentation Checklist:** Required artifacts for institutional-grade capital structure.
14. **MICOS Scorecard:** A self-assessment tool for capital structure maturity.

---

## 1. Strategic Function

### What is it?

The **Strategic Function** of the Capital Structure is to **engineer the hierarchy, cost, flexibility, and resilience of financial claims on the platform to optimize growth, control, risk absorption, and long-term durability.**

Capital structure is the financial skeleton of the institution. It determines:

- **Who provides capital:** Equity investors, debt providers, hybrid financiers.
- **In what form:** Common equity, preferred equity, senior debt, subordinated debt, mezzanine, convertible instruments.
- **At what cost:** The required return for each type of capital.
- **With what priority:** The order in which claims are paid.
- **With what control implications:** The governance rights that accompany different capital types.
- **With what downside protection:** The mechanisms that protect against loss.
- **With what refinancing optionality:** The ability to replace or restructure capital.

### Why does this matter?

Without structured capital architecture:

| Risk | Consequence |
|---|---|
| **Over-leverage** | The institution cannot service its debt. Financial distress or bankruptcy. |
| **Covenant breach** | Debt covenants are violated, triggering acceleration or penalties. |
| **Maturity wall** | Multiple debts mature at the same time, creating a refinancing crisis. |
| **Misaligned tenor** | Capital is raised for the wrong duration, creating a mismatch with asset life. |
| **Excessive cost of capital** | The institution pays too much for financing, destroying value. |
| **Hidden guarantees** | Founders or shareholders have personal guarantees, creating personal risk. |
| **Cross-default traps** | A default on one debt triggers defaults on others. |
| **Equity dilution shock** | New equity issuances dilute existing shareholders unexpectedly. |
| **Convertible overhang** | Convertible instruments create uncertainty and potential dilution. |
| **Liquidation preference distortion** | Preferences create perverse incentives or value extraction. |
| **Inability to refinance** | The institution cannot replace maturing debt, leading to default. |
| **Currency mismatch** | Debt is in a different currency than revenues, creating exchange rate risk. |
| **Collateral over-pledging** | The same assets are pledged to multiple lenders. |

### What is at stake?

| Stake | Consequence of Weak Capital Structure |
|---|---|
| **Solvency** | The institution may become insolvent. |
| **Control** | Debt holders or new equity holders may take control. |
| **Value** | Value is destroyed through excessive costs, dilution, or forced sales. |
| **Continuity** | Financial distress leads to institutional failure. |
| **Reputation** | Financial distress damages the institution's reputation. |

### How does it connect to the framework's overall purpose?

| Framework Purpose | Capital Structure Contribution |
|---|---|
| **Bankability** | Capital structure is the primary focus of institutional capital providers. |
| **Scalability** | Capital structure must support growth without excessive dilution or leverage. |
| **Survivability** | Capital structure must be resilient to financial shocks. |
| **Permanence** | Capital structure must support long-term continuity and intergenerational transfer. |

---

## 2. Scope Boundary

### What does this chapter govern?

Capital structure addresses the **financial claim hierarchy and cost architecture** of the institution. It governs:

| Domain | Description |
|---|---|
| **Equity vs. debt mix** | The proportion of equity and debt financing. |
| **Seniority hierarchy** | The order of claims in liquidation. |
| **Cost of capital** | The required return for each type of capital. |
| **Security and collateral** | The assets pledged to secure debt. |
| **Covenants and restrictions** | The conditions attached to debt. |
| **Refinancing mechanics** | How debt is refinanced. |
| **Liquidity buffers** | Cash reserves and other liquidity sources. |
| **Capital recycling** | How capital is redeployed. |
| **Dilution mechanics** | How equity issuances affect existing shareholders. |
| **Downside protection** | Mechanisms protecting against loss. |
| **Instrument design** | Convertible, mezzanine, and hybrid instruments. |

### What does this chapter NOT govern?

Capital structure defines **financial claim hierarchy and cost architecture**. It does not define decision authority or operational execution.

| Exclusion | Handled By |
|---|---|
| **Shareholder identity** | Chapter 1: Ownership Structure |
| **Board approval processes** | Chapter 2: Governance Structure |
| **Revenue generation** | Chapter 5: Cashflow & Revenue Structure |
| **Tax optimization** | Chapter 7: Tax Structure |
| **Licensing** | Chapter 8: Compliance & Licensing Structure |
| **Risk transfer via insurance** | Chapter 6: Risk & Guarantee Structure |
| **Operational budgeting** | Chapter 10: Operations Structure |
| **Compensation equity plans** | Chapter 12: Incentive Structure |

### Why does this boundary matter?

Scope clarity prevents overlap and conflict. When capital structure and other structures are confused, institutions suffer from:

- **Authority ambiguity:** Does the board or the shareholders approve capital raises?
- **Priority confusion:** Who gets paid first in a liquidation?
- **Tax misalignment:** Is capital structured optimally for tax purposes?
- **Control confusion:** Do debt covenants override governance authority?

### How is the boundary enforced?

| Enforcement Method | Description |
|---|---|
| **Explicit definitions** | Each chapter clearly defines its domain. |
| **Cross-references** | Chapters refer to each other to avoid duplication. |
| **Documentation discipline** | Different documents govern different domains. |
| **Capital priority matrix** | Claim priority is explicitly mapped. |

---

## 3. Dependency Position

### Prerequisites

Capital structure depends on:

| Prerequisite | Why It Is Required |
|---|---|
| **Legal Structure (Chapter 4)** | The institution must have legal capacity to issue capital instruments. |
| **Ownership Structure (Chapter 1)** | Economic rights clarity is required for capital design. |
| **Governance Structure (Chapter 2)** | Approval authority must be defined before capital can be raised. |

### Feeds Into

Capital structure is a prerequisite for:

| Dependent Chapter | Why It Depends on Capital Structure |
|---|---|
| **Cashflow & Revenue Structure (Chapter 5)** | Debt servicing capacity depends on cashflow. |
| **Risk & Guarantee Structure (Chapter 6)** | Default exposure depends on leverage. |
| **Tax Structure (Chapter 7)** | Interest deductibility and withholding depend on capital structure. |
| **Optionality & Exit Structure (Chapter 15)** | Exit outcomes depend on capital structure. |
| **Incentive Structure (Chapter 12)** | Equity dilution impacts incentive design. |
| **Adaptive System (Chapters 16-20)** | Strategic financing flexibility depends on capital structure. |
| **Legacy System (Chapters 21-25)** | Long-term solvency depends on capital structure. |

### Lateral Relationships

Capital structure also interacts with:

| Lateral Chapter | Relationship |
|---|---|
| **Risk & Guarantee Structure (Chapter 6)** | Risk management protects capital structure. |
| **Cashflow & Revenue Structure (Chapter 5)** | Cashflow services capital. |
| **Tax Structure (Chapter 7)** | Tax treatment affects cost of capital. |

### How does this dependency network function?

Capital structure is the **financial skeleton** of the institution. It must be designed after ownership and governance, and it must be completed before cashflow, risk, and tax structures can be optimized. If capital structure is weak, no other structure can compensate.

**Example:** If capital structure is over-leveraged, cashflow will be consumed by debt service, reducing the institution's ability to invest in operations or respond to shocks. Risk management will be focused on avoiding default rather than optimizing risk. Tax benefits of debt may be offset by excessive leverage.

---

## 4. Failure Modes

Capital structure failures are the third most common cause of institutional collapse (after ownership and governance failures). The following failure modes must be addressed in any capital structure design.

---

### Failure Mode: Over-Leverage Beyond Cashflow Capacity

**What is it?**

Over-leverage occurs when the institution has taken on more debt than its cashflow can service. The institution is unable to meet its debt obligations, leading to financial distress or default.

**How does it become a failure mode?**

Over-leverage becomes a failure mode when:

1. **Excessive debt:** The institution takes on debt beyond its cashflow capacity.

2. **Optimistic projections:** The institution assumes revenue growth that does not materialize.

3. **Cashflow shortfall:** Actual cashflow falls short of projections.

4. **Debt service failure:** The institution cannot make debt payments.

5. **Default:** The institution defaults on its debt obligations.

6. **Forced restructuring or bankruptcy:** The institution is forced into restructuring or bankruptcy.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Financial distress** | The institution struggles to meet obligations. |
| **Default** | The institution defaults on debt. |
| **Forced sale** | Assets are sold at depressed prices. |
| **Bankruptcy** | The institution files for bankruptcy. |
| **Control loss** | Debt holders take control. |
| **Value destruction** | Value is destroyed for equity holders. |

**What does it look like in practice?**

**Example: The Over-Leveraged Expansion**

*Expansion Holdings* is a growing retail company. To fund expansion, it takes on significant debt—5x EBITDA. The projections assume 20% annual revenue growth. After 18 months, revenue growth slows to 5% due to economic headwinds. EBITDA falls. The company cannot service its debt. It breaches covenants. Lenders force a restructuring. Existing equity is wiped out. The company is sold to a competitor at a discount.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Conservative leverage targets** | Leverage is kept at conservative levels (e.g., 2-3x EBITDA). |
| **Stress-testing** | Leverage is stress-tested against downside scenarios. |
| **Covenant headroom** | Covenants provide headroom for underperformance. |
| **Liquidity reserves** | Cash reserves are maintained for debt service. |
| **Debt service coverage** | DSCR is monitored and maintained above threshold. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage leverage and debt service capacity. |
| **Board** | To approve leverage levels. |
| **Management** | To execute within leverage targets. |
| **Capital Structure (This Chapter)** | To design sustainable capital structure. |

---

### Failure Mode: Covenant Breach Cascade

**What is it?**

A covenant breach cascade occurs when a breach of one debt covenant triggers a cascade of breaches across other debt agreements, leading to an acceleration of all debt.

**How does it become a failure mode?**

A covenant breach cascade becomes a failure mode when:

1. **Cross-default provisions:** Debt agreements include cross-default provisions.

2. **Covenant breach:** A covenant is breached in one agreement.

3. **Cascade:** The breach triggers breaches in other agreements.

4. **Acceleration:** All debt becomes due and payable.

5. **Default:** The institution cannot repay all debt.

6. **Restructuring or bankruptcy:** The institution is forced into restructuring or bankruptcy.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **All debt accelerated** | All debt becomes due and payable. |
| **Liquidity crisis** | The institution cannot repay all debt. |
| **Default** | The institution defaults on all debt. |
| **Control loss** | Lenders take control. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Cross-Default Trap**

*Industrial Technologies* has debt from three different lenders. All debt agreements include cross-default provisions. The company breaches a covenant on its smallest debt—a $10 million line of credit. The breach triggers cross-default provisions on the other two debts—$50 million and $100 million. All debt becomes due and payable. The company cannot repay the $160 million. It is forced into bankruptcy. The business is sold to a competitor.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Covenant review** | Review all covenants for cross-default provisions. |
| **Covenant headroom** | Maintain headroom in all covenants. |
| **Cross-default negotiation** | Negotiate cross-default provisions to limit cascades. |
| **Covenant monitoring** | Monitor covenants regularly. |
| **Early warning** | Identify covenant breaches early and remediate. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To monitor covenants and identify breaches. |
| **Legal Counsel** | To review and negotiate covenant provisions. |
| **Board** | To oversee covenant compliance. |
| **Risk Management** | To assess covenant risk. |

---

### Failure Mode: Maturity Wall Concentration

**What is it?**

A maturity wall occurs when multiple debt obligations mature at the same time (or within a short period), creating a concentration of refinancing risk.

**How does it become a failure mode?**

A maturity wall becomes a failure mode when:

1. **Concentrated maturities:** Multiple debts mature at the same time.

2. **Refinancing need:** The institution must refinance all debts simultaneously.

3. **Market conditions:** Market conditions are unfavorable for refinancing.

4. **Refinancing failure:** The institution cannot refinance its debts.

5. **Default:** The institution defaults on maturing debts.

6. **Forced restructuring:** The institution is forced into restructuring.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Refinancing risk** | The institution may not be able to refinance. |
| **Higher cost** | Refinancing may be at higher costs. |
| **Default** | The institution may default. |
| **Control loss** | Lenders may take control. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Maturity Wall**

*Commercial Properties* has three debt facilities. The first matures in 2024, the second in 2024, and the third in 2024. All three debts mature in the same year. The company plans to refinance them with a single new facility. In 2023, interest rates rise sharply and credit markets tighten. The company cannot secure a refinancing facility. It defaults on its debts. Lenders foreclose on properties. The company is sold at a discount.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Staggered maturities** | Stagger debt maturities so they do not all mature at once. |
| **Refinancing plan** | Develop a refinancing plan well before maturities. |
| **Contingency financing** | Secure contingency financing (e.g., a standby facility). |
| **Early refinancing** | Refinance early to avoid market timing risk. |
| **Liquidity reserves** | Maintain liquidity reserves for refinancing needs. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage maturity profiles and refinancing. |
| **Treasury** | To execute refinancing plans. |
| **Board** | To approve refinancing strategies. |

---

### Failure Mode: Misaligned Capital Tenor vs. Asset Life

**What is it?**

Capital tenor (the duration of the capital) is misaligned with the life of the assets being financed. Short-term capital finances long-term assets, or long-term capital finances short-term assets.

**How does it become a failure mode?**

Misaligned tenor becomes a failure mode when:

1. **Short-term debt finances long-term assets:** The institution uses short-term debt (e.g., 1-year loans) to finance long-term assets (e.g., 20-year infrastructure).

2. **Rollover risk:** The institution must repeatedly refinance the short-term debt.

3. **Refinancing failure:** The institution cannot refinance the debt.

4. **Forced sale:** The institution is forced to sell assets to repay debt.

5. **Value destruction:** Value is destroyed through forced sales.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Rollover risk** | The institution must repeatedly refinance. |
| **Refinancing failure** | The institution may not be able to refinance. |
| **Forced sale** | Assets are sold at distressed prices. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Mismatched Tenor**

*Infrastructure Development Partners* builds a 20-year toll road. It finances the construction with 5-year bank loans. The loans must be refinanced every 5 years. After 5 years, the road has not generated enough revenue to support a refinancing. The bank will not extend the loans. The company is forced to sell the road at a distressed price to repay the loans.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Tenor matching** | Match capital tenor with asset life. |
| **Long-term financing** | Use long-term debt (e.g., project finance bonds) for long-term assets. |
| **Refinancing buffer** | Build a buffer to cover refinancing risk. |
| **Cashflow alignment** | Align debt service with asset cashflows. |
| **Hedging** | Hedge interest rate and currency risk. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To ensure tenor matching. |
| **Treasury** | To structure financing. |
| **Board** | To approve financing strategies. |

---

### Failure Mode: Excessive Cost of Capital

**What is it?**

The institution pays a higher cost of capital than is justified by its risk profile. This reduces profitability and value.

**How does it become a failure mode?**

Excessive cost of capital becomes a failure mode when:

1. **Structural weakness:** The institution's capital structure is weak, increasing perceived risk.

2. **Poor market positioning:** The institution does not effectively market itself to capital providers.

3. **Inefficient capital mix:** The institution uses too much expensive capital (e.g., equity) and not enough cheap capital (e.g., debt).

4. **High required return:** Capital providers demand a high return because of perceived risk.

5. **Value destruction:** The high cost of capital reduces profitability and value.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Reduced profitability** | High capital costs reduce profitability. |
| **Lower valuation** | High cost of capital reduces valuation. |
| **Competitive disadvantage** | High capital costs create a competitive disadvantage. |
| **Limited growth** | High capital costs limit growth investment. |

**What does it look like in practice?**

**Example: The Inefficient Capital Mix**

*Renewable Energy Assets* is an infrastructure company with predictable, stable cashflows. It is financed 100% with equity. The cost of equity is 12%. By adding debt (which costs 6%), the company could reduce its weighted average cost of capital (WACC) to 8%. The company misses this opportunity. Its profitability is lower than competitors. Its valuation is lower. Its growth is constrained.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Optimal capital mix** | Use an optimal mix of equity and debt. |
| **Market positioning** | Position the institution effectively to capital providers. |
| **Cost of capital analysis** | Analyze and optimize the cost of capital. |
| **Capital market engagement** | Engage with capital markets proactively. |
| **Credit rating improvement** | Improve credit rating to lower cost of debt. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage cost of capital. |
| **Treasury** | To execute capital market transactions. |
| **Board** | To approve capital structure strategies. |

---

### Failure Mode: Hidden Personal Guarantees

**What is it?**

Founders, executives, or shareholders provide personal guarantees for the institution's debt. They are personally liable if the institution defaults.

**How does it become a failure mode?**

Hidden personal guarantees become a failure mode when:

1. **Personal guarantees exist:** Founders or shareholders provide personal guarantees for institutional debt.

2. **Institution defaults:** The institution defaults on its debt.

3. **Guarantee enforcement:** The lender enforces the personal guarantee.

4. **Personal assets at risk:** The guarantor loses personal assets—homes, savings, investments.

5. **Guarantor bankruptcy:** The guarantor is forced into personal bankruptcy.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Personal asset loss** | Guarantors lose personal assets. |
| **Personal bankruptcy** | Guarantors file for personal bankruptcy. |
| **Institutional instability** | Guarantor loss destabilizes the institution. |
| **Investor reluctance** | Investors will not invest if personal guarantees are required. |

**What does it look like in practice?**

**Example: The Personal Guarantee Trap**

*Family Bakery* is a growing bakery chain. The founder provides a personal guarantee for a $2 million loan. The business struggles. The bank enforces the guarantee. The founder loses her home, her savings, and her investments. She declares personal bankruptcy. The business is sold to a competitor. The founder loses everything.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Prohibit personal guarantees** | No personal guarantees for institutional debt. |
| **Limited guarantees** | If guarantees are required, limit them to a specific amount. |
| **Collateral substitution** | Use corporate assets as collateral instead of personal guarantees. |
| **Insurance** | Use insurance products to cover guarantee risk. |
| **Negotiate** | Negotiate with lenders to remove personal guarantees. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **Founders/Management** | To avoid personal guarantees. |
| **Board** | To approve guarantee structures. |
| **Legal Counsel** | To review and negotiate guarantee provisions. |

---

### Failure Mode: Cross-Default Traps

**What is it?**

Debt agreements include cross-default provisions, meaning a default on any one debt triggers default on all debts. This creates a cascade effect where a single default can bring down the entire institution.

**How does it become a failure mode?**

Cross-default traps become a failure mode when:

1. **Cross-default provisions exist:** Debt agreements include cross-default provisions.

2. **Default event:** A default occurs on one debt.

3. **Cascade:** The default triggers defaults on all debts.

4. **All debt accelerated:** All debts become due and payable.

5. **Inability to pay:** The institution cannot pay all debts.

6. **Bankruptcy:** The institution files for bankruptcy.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **All debt accelerated** | All debts become due and payable. |
| **Liquidity crisis** | The institution cannot pay all debts. |
| **Default** | The institution defaults on all debts. |
| **Control loss** | Lenders take control. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Cross-Default Trap (revisited)**

*Industrial Technologies* has debt from three different lenders. All agreements include cross-default provisions. The company breaches a covenant on its smallest debt, triggering cross-default provisions on all debts. All debts become due. The company cannot pay. It files for bankruptcy. The business is sold to a competitor.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Review covenants** | Review all covenants for cross-default provisions. |
| **Negotiate limitations** | Negotiate limitations on cross-default provisions. |
| **Covenant headroom** | Maintain headroom in all covenants. |
| **Covenant monitoring** | Monitor covenants regularly. |
| **Early warning** | Identify issues early and remediate. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To monitor covenants and identify breaches. |
| **Legal Counsel** | To review and negotiate covenant provisions. |
| **Board** | To oversee covenant compliance. |

---

### Failure Mode: Equity Dilution Shock

**What is it?**

A new equity issuance dilutes existing shareholders more than expected or without proper notice, creating a dilution shock.

**How does it become a failure mode?**

Equity dilution shock becomes a failure mode when:

1. **Unexpected dilution:** Existing shareholders are diluted without prior notice or without having anticipated the dilution.

2. **Value loss:** Existing shareholders suffer a significant loss of ownership percentage.

3. **Control loss:** Existing shareholders lose control of the institution.

4. **Conflict:** Existing shareholders challenge the issuance.

5. **Litigation:** Shareholders sue over dilution.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Value loss** | Existing shareholders lose value. |
| **Control loss** | Existing shareholders lose control. |
| **Conflict** | Shareholders challenge the issuance. |
| **Litigation** | Shareholders sue over dilution. |
| **Institutional instability** | Conflict destabilizes the institution. |

**What does it look like in practice?**

**Example: The Dilution Shock**

*Innovation Tech* has been financed by the founder (60%) and a VC firm (40%). The company needs additional capital. The founder assumes it will be debt. Instead, the board approves a new equity issuance that dilutes the founder to 40% and the VC to 30%, with a new investor taking 30%. The founder is shocked and angered. He sues the board for breach of fiduciary duty. The lawsuit drags on. The company's performance suffers. The founder eventually leaves.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Anti-dilution provisions** | Protect existing shareholders from dilution. |
| **Preemptive rights** | Existing shareholders have rights to participate in new issuances. |
| **Dilution modeling** | Model the impact of potential issuances. |
| **Shareholder approval** | Require shareholder approval for significant issuances. |
| **Communication** | Communicate dilution plans in advance. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **Board** | To approve issuances and protect shareholder interests. |
| **Management** | To communicate dilution plans. |
| **Shareholders** | To exercise preemptive rights. |
| **Capital Structure (This Chapter)** | To design dilution mechanisms. |

---

### Failure Mode: Inability to Refinance

**What is it?**

The institution cannot refinance its debt when it matures because market conditions are unfavorable, the institution's credit profile has deteriorated, or lenders are unwilling to lend.

**How does it become a failure mode?**

Inability to refinance becomes a failure mode when:

1. **Maturity:** Debt matures.

2. **Refinancing attempt:** The institution attempts to refinance.

3. **Failure:** The institution cannot secure refinancing.

4. **Default:** The institution defaults on maturing debt.

5. **Forced restructuring:** The institution is forced into restructuring.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Default** | The institution defaults on maturing debt. |
| **Forced restructuring** | The institution is forced into restructuring. |
| **Control loss** | Lenders take control. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Refinancing Failure**

*Commercial Properties* (from the earlier example) has three debt facilities maturing in 2024. In 2023, interest rates rise sharply and credit markets tighten. The company cannot secure a refinancing facility. It defaults on its debts. Lenders foreclose on properties. The company is sold at a discount.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Staggered maturities** | Stagger debt maturities to avoid concentration. |
| **Refinancing plan** | Develop a refinancing plan well before maturities. |
| **Contingency financing** | Secure contingency financing (e.g., a standby facility). |
| **Early refinancing** | Refinance early to avoid market timing risk. |
| **Liquidity reserves** | Maintain liquidity reserves for refinancing needs. |
| **Credit profile maintenance** | Maintain a strong credit profile. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage refinancing. |
| **Treasury** | To execute refinancing. |
| **Board** | To approve refinancing strategies. |

---

### Failure Mode: Currency Mismatch

**What is it?**

The institution has debt denominated in a currency different from its revenues. A currency movement can make debt service impossible.

**How does it become a failure mode?**

Currency mismatch becomes a failure mode when:

1. **Debt in foreign currency:** The institution has debt in a currency different from its revenues.

2. **Currency depreciation:** The domestic currency depreciates against the foreign currency.

3. **Debt service cost increases:** Debt service costs increase in domestic currency terms.

4. **Inability to pay:** The institution cannot pay its debt service.

5. **Default:** The institution defaults.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Increased debt service** | Debt service costs increase dramatically. |
| **Default** | The institution cannot pay debt service. |
| **Control loss** | Lenders take control. |
| **Value destruction** | Value is destroyed. |

**What does it look like in practice?**

**Example: The Currency Crisis**

*Emerging Markets Infrastructure* is an infrastructure company in an emerging market. It has $100 million in debt denominated in US dollars. Its revenues are in local currency. The local currency depreciates 40% against the dollar. Debt service costs increase by 67% in local currency terms. The company cannot pay its debt service. It defaults. Lenders take control of assets.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Currency matching** | Match debt currency with revenue currency. |
| **Hedging** | Hedge currency risk through derivatives. |
| **Natural hedge** | Generate revenues in the same currency as debt. |
| **Currency diversification** | Diversify currency exposure. |
| **Local currency financing** | Raise debt in local currency. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage currency risk. |
| **Treasury** | To execute hedges. |
| **Board** | To approve currency risk management strategies. |

---

### Failure Mode: Collateral Over-Pledging

**What is it?**

The same assets are pledged to multiple lenders, creating a situation where the collateral is insufficient to cover all claims in a default.

**How does it become a failure mode?**

Collateral over-pledging becomes a failure mode when:

1. **Multiple pledges:** The same assets are pledged to multiple lenders.

2. **Default event:** The institution defaults.

3. **Collateral insufficiency:** The collateral is insufficient to cover all claims.

4. **Intercreditor dispute:** Lenders dispute the priority of their claims.

5. **Value destruction:** Value is destroyed through litigation and dispute.

**What are the consequences?**

| Consequence | Description |
|---|---|
| **Intercreditor dispute** | Lenders dispute claim priority. |
| **Litigation** | Lenders sue each other. |
| **Value destruction** | Value is destroyed through litigation. |
| **Delayed resolution** | The default is not resolved quickly. |

**What does it look like in practice?**

**Example: The Over-Pledged Assets**

*Real Estate Holdings* owns a portfolio of properties. It pledges the properties to Bank A for a $50 million loan. It then pledges the same properties to Bank B for a $30 million loan. The company defaults. Both banks claim the properties. Bank A argues it has priority. Bank B argues it also has a claim. The banks litigate. The properties lose value. The company's assets are tied up for years.

**How is it prevented?**

| Prevention Strategy | How It Works |
|---|---|
| **Collateral tracking** | Track all collateral pledges. |
| **Collateral sufficiency** | Ensure collateral is sufficient for all claims. |
| **Intercreditor agreements** | Enter into intercreditor agreements defining priority. |
| **Pledge restrictions** | Restrict the percentage of assets that can be pledged. |
| **Security registers** | Maintain a register of all security interests. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To manage collateral and pledges. |
| **Legal Counsel** | To negotiate intercreditor agreements. |
| **Board** | To approve collateral pledges. |

---

## 5. Design Principles

### Principle 1: Capital Must Match Asset Life

**What does this principle mean?**

The duration of capital must match the life of the assets being financed. Long-term assets should be financed with long-term capital. Short-term assets should be financed with short-term capital.

**Why is this a principle?**

Misaligned tenor creates rollover risk. When short-term capital finances long-term assets, the institution must repeatedly refinance, creating the risk of refinancing failure.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Tenor matching** | Match capital tenor with asset life. |
| **Long-term financing** | Use long-term debt for long-term assets. |
| **Short-term financing** | Use short-term debt for short-term assets. |
| **Refinancing plan** | Develop a refinancing plan for any misalignment. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Cost vs. tenor** | Longer-term capital is typically more expensive. |
| **Flexibility vs. certainty** | Long-term capital is less flexible but more certain. |

**What happens if it is violated?**

Rollover risk, refinancing failure, and potential default.

---

### Principle 2: Leverage Must Be Serviceable Under Stress

**What does this principle mean?**

Leverage must be serviceable not only in the base case but also under stress scenarios. The institution must be able to service its debt even if revenue declines, costs increase, or interest rates rise.

**Why is this a principle?**

Over-leverage is the most common cause of financial distress. If leverage cannot be serviced under stress, the institution will default when conditions deteriorate.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Stress-testing** | Stress-test leverage against downside scenarios. |
| **Conservative leverage** | Maintain conservative leverage levels. |
| **Covenant headroom** | Maintain headroom in debt covenants. |
| **Liquidity reserves** | Maintain reserves for stress periods. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Growth vs. resilience** | Lower leverage reduces growth but increases resilience. |
| **Return vs. risk** | Higher leverage increases return but increases risk. |

**What happens if it is violated?**

Default, financial distress, and potential insolvency.

---

### Principle 3: Seniority Must Be Unambiguous

**What does this principle mean?**

The priority of claims in liquidation must be clearly defined and unambiguous. There must be no doubt about who gets paid first, second, and third.

**Why is this a principle?**

Seniority ambiguity leads to disputes in default, intercreditor litigation, and value destruction. Financiers require clarity on their position in the capital stack.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Capital priority matrix** | A clear matrix of claim priority. |
| **Intercreditor agreements** | Agreements defining priority among lenders. |
| **Security registers** | Registers of all security interests. |
| **Subordination agreements** | Agreements subordinating claims. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Clarity vs. complexity** | Clear seniority may require more complex documentation. |
| **Protection vs. cost** | Senior debt is cheaper but may require security. |

**What happens if it is violated?**

Intercreditor disputes, litigation, and value destruction.

---

### Principle 4: No Maturity Cliffs Without Refinancing Visibility

**What does this principle mean?**

There must be no maturity cliffs—where a large proportion of debt matures at the same time—unless there is clear visibility on refinancing capacity.

**Why is this a principle?**

Maturity cliffs create refinancing risk. If the institution cannot refinance when debts mature, it defaults.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Staggered maturities** | Stagger debt maturities across different dates. |
| **Refinancing plan** | Develop a refinancing plan well before maturities. |
| **Contingency financing** | Secure contingency financing. |
| **Early refinancing** | Refinance early to avoid market timing risk. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Flexibility vs. certainty** | Staggered maturities provide flexibility but may be more expensive. |
| **Cost vs. resilience** | Maintaining liquidity reserves has a cost but increases resilience. |

**What happens if it is violated?**

Refinancing failure, default, and potential insolvency.

---

### Principle 5: Downside Protection Must Not Paralyze Upside

**What does this principle mean?**

Downside protection mechanisms (such as covenants, security, and guarantees) must protect against loss without paralyzing the institution's ability to create value.

**Why is this a principle?**

Excessive downside protection creates paralysis. Covenants that are too restrictive prevent value creation. Security that is too extensive prevents additional financing.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Covenant negotiation** | Negotiate reasonable covenants. |
| **Security limits** | Limit security to what is necessary. |
| **Covenant headroom** | Provide headroom for underperformance. |
| **Covenant flexibility** | Allow for covenant modifications if needed. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Protection vs. flexibility** | More protection reduces flexibility. |
| **Lender requirements vs. institutional needs** | Lenders require protection, but the institution needs flexibility. |

**What happens if it is violated?**

Paralysis, reduced value creation, or covenant breaches.

---

### Principle 6: Cost of Capital Must Be Risk-Adjusted, Not Cosmetic

**What does this principle mean?**

The cost of capital must reflect the underlying risk of the institution. It cannot be artificially reduced through cosmetic measures (e.g., short-term fixes that increase long-term risk).

**Why is this a principle?**

Cosmetic cost reduction creates hidden risks. The institution may appear to have a low cost of capital but actually be taking on excessive risk.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Risk-adjusted cost of capital** | Calculate WACC based on risk. |
| **Transparent pricing** | Ensure pricing reflects true risk. |
| **Credit rating** | Maintain an accurate credit rating. |
| **Market feedback** | Listen to market feedback on capital costs. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Cost vs. transparency** | Transparent pricing may be higher but more accurate. |
| **Short-term vs. long-term** | Short-term cost reduction may increase long-term risk. |

**What happens if it is violated?**

Hidden risks, financial distress, and potential default.

---

### Principle 7: Liquidity Buffers Must Be Structural, Not Optimistic

**What does this principle mean?**

Liquidity buffers—cash reserves and other liquidity sources—must be based on realistic, not optimistic, assumptions. They must be structural, not dependent on favorable conditions.

**Why is this a principle?**

Optimistic liquidity assumptions lead to liquidity crises. When conditions deteriorate, optimistic buffers disappear, leaving the institution exposed.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Conservative assumptions** | Use conservative assumptions for liquidity planning. |
| **Stress-testing** | Stress-test liquidity under downside scenarios. |
| **Diversified sources** | Maintain diversified liquidity sources. |
| **Contingency facilities** | Secure contingency financing. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Liquidity vs. efficiency** | Holding liquidity has a cost but increases resilience. |
| **Cost vs. resilience** | Maintaining liquidity reserves reduces profitability but increases survival. |

**What happens if it is violated?**

Liquidity crisis, default, and potential insolvency.

---

### Principle 8: Dilution Must Be Modeled Before Issuance

**What does this principle mean?**

The impact of any equity issuance on existing shareholders must be modeled and communicated before the issuance. There must be no dilution shocks.

**Why is this a principle?**

Dilution shocks create conflict, litigation, and institutional instability. Existing shareholders must be able to anticipate dilution.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Dilution modeling** | Model the impact of any issuance. |
| **Preemptive rights** | Provide preemptive rights to existing shareholders. |
| **Shareholder communication** | Communicate dilution plans in advance. |
| **Anti-dilution provisions** | Include anti-dilution protections. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Protection vs. flexibility** | Anti-dilution provisions protect shareholders but reduce flexibility. |
| **Communication vs. confidentiality** | Advance communication may reveal strategic plans. |

**What happens if it is violated?**

Conflict, litigation, and institutional instability.

---

### Principle 9: Refinancing Optionality Must Be Preserved

**What does this principle mean?**

The institution must preserve the ability to refinance its debt. It must not take actions that prevent or limit refinancing.

**Why is this a principle?**

Refinancing optionality is essential for financial resilience. Without it, the institution is trapped with its existing capital structure.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Refinancing plan** | Develop a refinancing plan. |
| **Covenant discipline** | Avoid covenants that prevent refinancing. |
| **Market engagement** | Engage with capital markets regularly. |
| **Credit profile maintenance** | Maintain a strong credit profile. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Optionality vs. cost** | Preserving optionality may have a cost. |
| **Flexibility vs. certainty** | Optionality provides flexibility but may be more expensive. |

**What happens if it is violated?**

Refinancing failure, default, and potential insolvency.

---

### Principle 10: Collateral Must Not Compromise Operational Control

**What does this principle mean?**

Collateral pledges must not compromise the institution's ability to operate and control its assets. The institution must retain operational control even if assets are pledged.

**Why is this a principle?**

Collateral pledges that restrict operational control create paralysis. The institution cannot manage its assets effectively.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Security negotiation** | Negotiate security that does not restrict operations. |
| **Operational controls** | Retain operational control of pledged assets. |
| **Lender covenants** | Avoid covenants that restrict operations. |
| **Security limits** | Limit security to what is necessary. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Protection vs. control** | Security provides protection but may reduce operational control. |
| **Lender requirements vs. institutional needs** | Lenders require security, but the institution needs operational control. |

**What happens if it is violated?**

Operational paralysis, reduced value creation, and potential default.

---

### Principle 11: Capital Stack Must Be Legible to Future Investors

**What does this principle mean?**

The capital stack must be clear, transparent, and understandable to future investors. New investors must be able to evaluate the capital structure quickly and confidently.

**Why is this a principle?**

Capital opacity is a red flag for future investors. If the capital stack is complex or opaque, investors will demand a higher return or will not invest at all.

**How is it implemented?**

| Implementation Method | How It Works |
|---|---|
| **Clear documentation** | Document the capital stack clearly. |
| **Transparency** | Be transparent about all capital structures. |
| **Simplicity** | Keep the capital stack as simple as possible. |
| **Investor engagement** | Engage with investors proactively. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Simplicity vs. sophistication** | Simpler structures are more legible but may not be optimal. |
| **Transparency vs. confidentiality** | Transparency may reveal competitive information. |

**What happens if it is violated?**

Investor reluctance, higher cost of capital, and difficulty raising capital.

---

## 6. Structural Components

### Component Category: Equity Layer

**What is it?**

The equity layer is the most junior part of the capital stack. Equity holders bear the residual risk and receive the residual returns. They are paid last in liquidation.

**What does it include?**

| Instrument | Description |
|---|---|
| **Common equity** | The most junior class of equity. Holders have voting rights and receive residual returns. |
| **Preferred equity** | Equity with preferences on dividends or liquidation. Typically has limited or no voting rights. |
| **Liquidation preferences** | Preferred equity holders receive a preference on liquidation proceeds. |
| **Anti-dilution provisions** | Protections against dilution of equity holdings. |
| **Dividend rights** | Rights to receive dividends. |
| **Participation rights** | Rights to participate in distributions beyond preferences. |
| **Conversion mechanics** | How preferred equity can be converted to common equity. |
| **Redemption rights** | Rights to redeem preferred equity. |

**How do they function?**

| Instrument | Function |
|---|---|
| **Common equity** | Provides residual returns and voting rights. |
| **Preferred equity** | Provides priority return and reduces risk. |
| **Liquidation preferences** | Protects preferred equity holders in liquidation. |
| **Anti-dilution provisions** | Protects existing shareholders from dilution. |
| **Dividend rights** | Provides return to equity holders. |
| **Participation rights** | Provides participation in upside. |
| **Conversion mechanics** | Enables conversion to common equity. |
| **Redemption rights** | Provides exit for preferred equity. |

**How are they structured?**

Equity instruments are structured in a hierarchy:

| Level | Instrument | Seniority |
|---|---|---|
| **Most junior** | Common equity | Lowest priority |
| **Intermediate** | Preferred equity | Higher priority than common |
| **Most senior** | Preferred with preferences | Highest priority in equity |

**Who owns them?**

| Owner | Responsibility |
|---|---|
| **Founders/Management** | Common equity holders. |
| **Institutional investors** | Preferred equity holders. |
| **Employees** | May hold common equity through ESOP. |

**Why are they necessary?**

Equity provides the risk capital that absorbs losses and supports the institution's operations.

---

### Component Category: Debt Layer

**What is it?**

The debt layer is the senior part of the capital stack. Debt holders have claims on cashflows and assets before equity holders. They are paid before equity in liquidation.

**What does it include?**

| Instrument | Description |
|---|---|
| **Senior secured debt** | Debt secured by specific assets. Highest priority in liquidation. |
| **Senior unsecured debt** | Debt not secured by specific assets. Claims on general assets of the institution. |
| **Subordinated debt** | Debt that is junior to senior debt. Paid after senior debt in liquidation. |
| **Mezzanine financing** | A hybrid of debt and equity. Subordinated to senior debt but has equity-like features. |
| **Convertible debt** | Debt that can be converted into equity. |
| **Revolving credit facility** | A flexible line of credit that can be drawn and repaid. |
| **Term loans** | Debt with a fixed maturity. |
| **Project finance structures** | Non-recourse debt secured by project assets. |

**How do they function?**

| Instrument | Function |
|---|---|
| **Senior secured debt** | Provides low-cost financing secured by assets. |
| **Senior unsecured debt** | Provides financing without specific security. |
| **Subordinated debt** | Provides financing with higher risk and return. |
| **Mezzanine financing** | Provides bridge between debt and equity. |
| **Convertible debt** | Provides debt financing with equity conversion option. |
| **Revolving credit facility** | Provides flexible working capital financing. |
| **Term loans** | Provides fixed-term financing. |
| **Project finance structures** | Provides non-recourse project financing. |

**How are they structured?**

Debt instruments are structured in a hierarchy:

| Level | Instrument | Seniority |
|---|---|---|
| **Most senior** | Senior secured debt | Highest priority |
| **Intermediate** | Senior unsecured debt | Lower priority than secured |
| **Junior** | Subordinated debt | Lower priority than unsecured |
| **Mezzanine** | Mezzanine financing | Highest cost, lowest priority in debt |

**Who owns them?**

| Owner | Responsibility |
|---|---|
| **Banks** | Senior secured and unsecured debt. |
| **Institutional investors** | Subordinated debt, mezzanine, convertible debt. |
| **Bond holders** | Senior unsecured debt through bond issuances. |

**Why are they necessary?**

Debt provides lower-cost financing than equity. It allows the institution to leverage its capital base.

---

### Component Category: Hybrid Instruments

**What is it?**

Hybrid instruments combine features of equity and debt. They provide flexibility in capital structure design.

**What does it include?**

| Instrument | Description |
|---|---|
| **Preferred shares with debt-like features** | Preferred equity with fixed dividends and redemption rights. |
| **Convertible notes** | Debt that can be converted into equity. |
| **SAFE-style instruments** | Simple Agreement for Future Equity. |
| **Revenue-based financing** | Financing repaid as a percentage of revenue. |
| **Warrants** | Rights to purchase equity at a fixed price. |
| **Structured equity** | Equity with customized rights and preferences. |

**How do they function?**

| Instrument | Function |
|---|---|
| **Preferred shares with debt-like features** | Provides fixed return with limited risk. |
| **Convertible notes** | Provides debt financing with equity upside. |
| **SAFE-style instruments** | Provides early-stage financing with conversion to equity. |
| **Revenue-based financing** | Provides financing repaid from revenue. |
| **Warrants** | Provides equity upside for debt holders. |
| **Structured equity** | Provides customized financing. |

**How are they structured?**

Hybrid instruments are structured with features from both debt and equity:

| Instrument | Debt Features | Equity Features |
|---|---|---|
| **Preferred shares** | Fixed dividends, redemption | Equity participation |
| **Convertible notes** | Interest, maturity | Conversion to equity |
| **SAFE** | None | Conversion to equity |
| **Revenue-based financing** | Repayment schedule | Revenue participation |
| **Warrants** | None | Equity purchase right |
| **Structured equity** | Fixed return | Equity participation |

**Who owns them?**

| Owner | Responsibility |
|---|---|
| **Institutional investors** | Hybrid instruments. |
| **Venture capital** | Convertible notes, SAFE. |
| **Revenue-based lenders** | Revenue-based financing. |

**Why are they necessary?**

Hybrid instruments provide flexibility in capital structure design. They can bridge gaps between debt and equity, providing financing that meets specific needs.

---

### Component Category: Protection Mechanisms

**What is it?**

Protection mechanisms protect the institution and its stakeholders from financial loss.

**What does it include?**

| Instrument | Description |
|---|---|
| **Security agreements** | Agreements securing debt with assets. |
| **Collateral registry filings** | Filings of security interests. |
| **Guarantee structures** | Guarantees of debt obligations. |
| **Intercreditor agreements** | Agreements defining priority among lenders. |
| **Subordination agreements** | Agreements subordinating claims. |
| **Covenant package** | Covenants protecting lenders and investors. |
| **Financial ratio tests** | Tests ensuring financial health. |
| **Negative pledge clauses** | Clauses preventing further pledges. |

**How do they function?**

| Instrument | Function |
|---|---|
| **Security agreements** | Secures debt with assets. |
| **Collateral registry filings** | Notifies other creditors of security interests. |
| **Guarantee structures** | Provides additional protection for debt holders. |
| **Intercreditor agreements** | Defines priority among lenders. |
| **Subordination agreements** | Subordinates claims to senior claims. |
| **Covenant package** | Protects lenders and investors. |
| **Financial ratio tests** | Ensures financial health. |
| **Negative pledge clauses** | Prevents over-pledging of assets. |

**How are they structured?**

Protection mechanisms are structured to protect the most senior claims first:

| Level | Protection | Purpose |
|---|---|---|
| **Senior secured** | Security agreements, collateral filings | Protects senior secured lenders. |
| **Senior unsecured** | Covenants, guarantees | Protects senior unsecured lenders. |
| **Junior debt** | Subordination agreements | Protects junior debt holders. |
| **Equity** | Anti-dilution provisions | Protects equity holders. |

**Who owns them?**

| Owner | Responsibility |
|---|---|
| **Lenders** | Require protection mechanisms. |
| **Borrower** | Provides protection mechanisms. |
| **Legal Counsel** | Drafts protection documents. |

**Why are they necessary?**

Protection mechanisms make financing possible. Without them, lenders would not provide capital or would demand excessive returns.

---

### Component Category: Liquidity & Stability Tools

**What is it?**

Liquidity and stability tools ensure the institution can meet its financial obligations and withstand shocks.

**What does it include?**

| Instrument | Description |
|---|---|
| **Cash reserve policy** | Policy on maintaining cash reserves. |
| **Debt service reserve account (DSRA)** | A reserve account for debt service. |
| **Hedging contracts** | Contracts hedging interest rate, currency, or commodity risk. |
| **Refinancing plan** | A plan for refinancing debt. |
| **Capital recycling policy** | A policy on redeploying capital. |

**How do they function?**

| Instrument | Function |
|---|---|
| **Cash reserve policy** | Ensures liquidity. |
| **Debt service reserve account** | Provides a buffer for debt service. |
| **Hedging contracts** | Protects against financial risks. |
| **Refinancing plan** | Ensures refinancing capacity. |
| **Capital recycling policy** | Ensures capital efficiency. |

**How are they structured?**

Liquidity tools are structured to provide a cushion against financial shocks:

| Tool | Purpose |
|---|---|
| **Cash reserves** | Provides a liquidity buffer. |
| **DSRA** | Provides a buffer for debt service. |
| **Hedging** | Protects against financial risks. |
| **Refinancing plan** | Ensures refinancing capacity. |

**Who owns them?**

| Owner | Responsibility |
|---|---|
| **CFO/Treasury** | Maintain liquidity tools. |
| **Board** | Approve liquidity policies. |

**Why are they necessary?**

Liquidity tools ensure the institution can survive financial shocks and meet its obligations.

---

## 7. Architecture Patterns

### Pattern 1: Equity-Heavy Growth Model

**What is it?**

A capital structure dominated by equity financing. The institution uses significant equity and minimal debt to fund growth.

**What problem does it address?**

Reduces financial risk. Provides flexibility for growth. Avoids the constraints of debt covenants.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **High equity** | 70-100% equity financing. |
| **Low debt** | 0-30% debt financing. |
| **Growth focus** | Capital is used for growth, not fixed assets. |
| **Flexibility** | No debt covenants constraining operations. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Low financial risk** | Debt service is not a constraint. |
| **High dilution** | Equity issuances dilute existing shareholders. |
| **Higher cost of capital** | Equity is more expensive than debt. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Risk vs. cost** | Lower risk but higher cost of capital. |
| **Flexibility vs. dilution** | More flexibility but more dilution. |
| **Growth vs. control** | Growth requires equity, which dilutes control. |

**When is it appropriate?**

Appropriate when:

- The institution is in a high-growth phase.
- The institution does not have assets to secure debt.
- The institution cannot service debt due to uncertain cashflows.
- The institution values flexibility over cost of capital.

**What are known deployments?**

| Example | Context |
|---|---|
| **Startups** | High-growth technology companies. |
| **Venture-backed companies** | VC-backed growth companies. |
| **Research-intensive companies** | Companies with uncertain cashflows. |

---

### Pattern 2: Leveraged Expansion Model

**What is it?**

A capital structure using significant debt to finance expansion. The institution uses leverage to increase returns.

**What problem does it address?**

Increases return on equity. Enables large-scale expansion without significant equity dilution.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Moderate equity** | 30-50% equity financing. |
| **High debt** | 50-70% debt financing. |
| **Expansion focus** | Capital is used for expansion. |
| **Covenants** | Debt covenants constrain operations. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Higher financial risk** | Debt service is a significant constraint. |
| **Lower dilution** | Less equity dilution. |
| **Lower cost of capital** | Debt is cheaper than equity. |
| **Covenant constraints** | Operations are constrained by debt covenants. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Return vs. risk** | Higher return but higher risk. |
| **Dilution vs. leverage** | Lower dilution but higher leverage. |
| **Growth vs. covenants** | Growth with leverage but constrained by covenants. |

**When is it appropriate?**

Appropriate when:

- The institution has stable, predictable cashflows.
- The institution has assets to secure debt.
- The institution wants to increase return on equity.
- The institution has a strong balance sheet to absorb risk.

**What are known deployments?**

| Example | Context |
|---|---|
| **LBOs** | Leveraged buyouts. |
| **Mature companies** | Companies with stable cashflows. |
| **Infrastructure** | Asset-backed infrastructure financing. |

---

### Pattern 3: Asset-Backed Financing Model

**What is it?**

A capital structure where debt is secured by specific assets. The institution borrows against its assets.

**What problem does it address?**

Provides lower-cost financing. Enables financing based on asset value rather than cashflow.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Asset base** | Assets are the basis for financing. |
| **Secured debt** | Debt is secured by assets. |
| **Asset valuation** | Debt is based on asset value. |
| **Non-recourse** | Debt is typically non-recourse to the institution. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Asset-based financing** | Financing is based on asset value. |
| **Non-recourse** | The institution is not personally liable. |
| **Asset control** | Lenders may control assets if default occurs. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Cost vs. control** | Lower cost but may lose asset control. |
| **Non-recourse vs. cost** | Non-recourse financing is more expensive. |

**When is it appropriate?**

Appropriate when:

- The institution has significant assets.
- The institution wants to finance based on asset value.
- The institution wants non-recourse financing.

**What are known deployments?**

| Example | Context |
|---|---|
| **Real estate** | Mortgage-backed financing. |
| **Infrastructure** | Project finance. |
| **Receivables** | Factoring and receivables financing. |

---

### Pattern 4: Project Finance Ring-Fence Model

**What is it?**

A capital structure where a specific project is financed on a non-recourse basis through a ring-fenced SPV (Special Purpose Vehicle). The project's assets and cashflows are the only basis for repayment.

**What problem does it address?**

Isolates project risk from the parent institution. Enables financing without recourse to the parent.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **SPV** | A ring-fenced SPV owns the project. |
| **Non-recourse debt** | Debt is non-recourse to the parent. |
| **Project cashflows** | Repayment is from project cashflows. |
| **Project assets** | Assets secure the debt. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Risk isolation** | Project risk is isolated from the parent. |
| **Non-recourse** | The parent is not liable for project debt. |
| **Project control** | Lenders have control over the project in default. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Risk isolation vs. cost** | Risk isolation but higher cost. |
| **Control vs. protection** | Parent loses control if project fails. |

**When is it appropriate?**

Appropriate when:

- The institution wants to isolate project risk.
- The project has stable, predictable cashflows.
- The project is large and capital-intensive.
- The parent does not want to guarantee project debt.

**What are known deployments?**

| Example | Context |
|---|---|
| **Infrastructure projects** | Toll roads, power plants, airports. |
| **Energy projects** | Renewable energy projects. |
| **Real estate** | Large real estate developments. |

---

### Pattern 5: Venture Capital Stack (Preferred-Heavy)

**What is it?**

A capital structure dominated by preferred equity from venture capital investors. The institution uses VC financing to fund growth.

**What problem does it address?**

Provides growth capital without requiring collateral or cashflow.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **VC financing** | Financing from venture capital firms. |
| **Preferred equity** | Investors hold preferred equity. |
| **Liquidation preferences** | Investors have preferences on liquidation. |
| **Anti-dilution** | Investors have anti-dilution protection. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **VC control** | VC investors have significant control. |
| **Founder dilution** | Founders are diluted significantly. |
| **Exit pressure** | VC investors pressure for exit. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Capital vs. control** | VC capital comes with loss of control. |
| **Growth vs. dilution** | Growth comes with significant dilution. |

**When is it appropriate?**

Appropriate when:

- The institution is a high-growth startup.
- The institution cannot access debt financing.
- The institution needs significant growth capital.

**What are known deployments?**

| Example | Context |
|---|---|
| **Tech startups** | VC-backed technology companies. |
| **Life sciences** | VC-backed biotech companies. |

---

### Pattern 6: Private Equity Leveraged Buyout Stack

**What is it?**

A capital structure dominated by debt used to finance a private equity acquisition. The institution uses significant leverage to finance the buyout.

**What problem does it address?**

Enables acquisition with limited equity. Increases returns for PE investors.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **PE equity** | PE investors provide equity. |
| **Senior debt** | Senior debt from banks. |
| **Subordinated debt** | Subordinated debt from institutional investors. |
| **Mezzanine** | Mezzanine financing. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **PE control** | PE investors control the institution. |
| **High leverage** | The institution is highly leveraged. |
| **Debt constraints** | Debt covenants constrain operations. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Return vs. risk** | High return but high risk. |
| **Control vs. leverage** | PE control but high leverage. |

**When is it appropriate?**

Appropriate when:

- The institution is being acquired by a PE firm.
- The institution has stable cashflows.
- The institution can support significant leverage.

**What are known deployments?**

| Example | Context |
|---|---|
| **LBOs** | Leveraged buyouts of mature companies. |
| **Carve-outs** | PE acquisitions of corporate divisions. |

---

### Pattern 7: Convertible Bridge-to-Equity Model

**What is it?**

A capital structure using convertible debt as a bridge to future equity financing. The convertible debt converts into equity at a future financing round.

**What problem does it address?**

Provides immediate capital with a clear path to equity conversion. Bridges the gap between financing rounds.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Convertible notes** | Debt that converts to equity. |
| **Conversion trigger** | Conversion at future equity financing. |
| **Discount** | Investors receive a discount on conversion. |
| **Valuation cap** | A cap on valuation for conversion. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Debt before conversion** | Debt holders have creditor rights. |
| **Equity after conversion** | Conversion creates equity holders. |
| **Control** | Control shifts upon conversion. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Speed vs. cost** | Fast financing but potentially dilutive. |
| **Debt vs. equity** | Debt before conversion, equity after. |

**When is it appropriate?**

Appropriate when:

- The institution needs bridging capital.
- The institution expects a future equity financing.
- The institution wants to defer valuation.

**What are known deployments?**

| Example | Context |
|---|---|
| **Startups** | Bridge financing between rounds. |
| **Growth companies** | Convertible bridge to Series A. |

---

### Pattern 8: Sovereign Co-Investment Model

**What is it?**

A capital structure where sovereign entities (e.g., sovereign wealth funds, development finance institutions) co-invest with private investors.

**What problem does it address?**

Provides large-scale capital. Provides political and regulatory support. De-risks investment.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Sovereign equity** | Sovereign entities hold equity. |
| **Private equity** | Private investors hold equity. |
| **Co-investment** | Both invest together. |
| **Governance** | Hybrid governance structure. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Sovereign influence** | Sovereign entities have influence. |
| **Private control** | Private investors may have control. |
| **Hybrid governance** | Governance is a balancing act. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Capital vs. sovereignty** | Sovereign capital comes with political considerations. |
| **Support vs. independence** | Sovereign support may reduce independence. |

**When is it appropriate?**

Appropriate when:

- The institution needs large-scale capital.
- The institution operates in a sector with state involvement.
- The institution needs political and regulatory support.

**What are known deployments?**

| Example | Context |
|---|---|
| **Infrastructure projects** | Sovereign co-investment in infrastructure. |
| **Energy projects** | Sovereign co-investment in energy. |
| **DFI investments** | DFI co-investment in development projects. |

---

### Pattern 9: Hybrid Mezzanine Layered Model

**What is it?**

A capital structure with multiple layers of debt, including mezzanine financing between senior debt and equity.

**What problem does it address?**

Optimizes the capital structure for cost and flexibility. Provides capital that senior debt cannot provide.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Senior debt** | Senior secured debt. |
| **Mezzanine** | Mezzanine financing. |
| **Equity** | Equity financing. |
| **Layers** | Multiple layers of debt. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Optimized cost** | Lower cost than equity. |
| **Flexibility** | Mezzanine provides flexibility. |
| **Complexity** | Multiple layers create complexity. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Cost vs. complexity** | Lower cost but more complexity. |
| **Flexibility vs. constraints** | Mezzanine provides flexibility but with constraints. |

**When is it appropriate?**

Appropriate when:

- The institution needs to optimize its capital structure.
- The institution cannot raise sufficient senior debt.
- The institution wants to avoid equity dilution.

**What are known deployments?**

| Example | Context |
|---|---|
| **Growth companies** | Mezzanine financing for growth. |
| **Buyouts** | Mezzanine financing for buyouts. |

---

### Pattern 10: Recapitalization Model

**What is it?**

A capital structure where the institution restructures its capital—replacing equity with debt, debt with equity, or restructuring existing debt.

**What problem does it address?**

Optimizes the capital structure for changing circumstances. Reduces cost of capital. Provides liquidity to shareholders.

**How is it structured?**

| Structure Element | Description |
|---|---|
| **Debt issuance** | New debt is issued. |
| **Equity buyback** | Equity is bought back. |
| **Debt restructuring** | Existing debt is restructured. |
| **Dividend recap** | Debt is used to pay dividends. |

**What are the control consequences?**

| Consequence | Description |
|---|---|
| **Optimization** | Capital structure is optimized. |
| **Liquidity** | Shareholders receive liquidity. |
| **Leverage** | Leverage may increase. |

**What are the trade-offs?**

| Trade-off | Consideration |
|---|---|
| **Optimization vs. risk** | Optimization may increase risk. |
| **Liquidity vs. control** | Liquidity may reduce control. |

**When is it appropriate?**

Appropriate when:

- The institution's capital structure is suboptimal.
- The institution wants to provide liquidity to shareholders.
- The institution wants to reduce the cost of capital.

**What are known deployments?**

| Example | Context |
|---|---|
| **Dividend recap** | PE-owned companies. |
| **Debt restructuring** | Companies with underperforming debt. |

---

## 8. Capital Priority Matrix

### What is the purpose of this matrix?

The Capital Priority Matrix is a tool for mapping claim priority in the capital structure. It ensures that there is no ambiguity about who gets paid first, second, and third in a liquidation or distribution.

### What does the matrix reveal?

| Insight | What It Shows |
|---|---|
| **Seniority clarity** | Whether claim priority is clearly defined. |
| **Priority alignment** | Whether priority aligns with risk exposure. |
| **Complexity** | Whether the capital structure is overly complex. |
| **Risk allocation** | How risk is allocated among capital providers. |

### How is it used?

The Capital Priority Matrix is populated for every institution, documenting:

1. The instrument type.
2. The seniority rank.
3. The security status.
4. The return type.
5. The control rights.
6. The maturity.
7. The refinancing risk.

### What does each column represent?

| Column | Description |
|---|---|
| **Instrument** | The type of capital instrument. |
| **Seniority Rank** | The priority order in liquidation. |
| **Security** | Whether the instrument is secured. |
| **Return Type** | The type of return (e.g., interest, dividends). |
| **Control Rights** | The control rights of the instrument. |
| **Maturity** | The maturity of the instrument. |
| **Refinancing Risk** | The risk of refinancing failure. |

### How is it completed?

The matrix is completed through:

1. **Reviewing capital documents:** Extract all priority and ranking provisions.
2. **Consulting intercreditor agreements:** Review agreements defining priority.
3. **Conducting interviews:** Confirm priority with capital providers.
4. **Documenting the matrix:** Record all findings in the matrix format.

### Capital Priority Matrix Template

| Instrument | Seniority Rank | Security | Return Type | Control Rights | Maturity | Refinancing Risk |
|---|---|---|---|---|---|---|
| Senior secured debt | 1 | Yes | Interest | Limited | 5 years | Low |
| Senior unsecured debt | 2 | No | Interest | Limited | 5 years | Moderate |
| Mezzanine | 3 | No | Interest + Equity | Limited | 7 years | High |
| Preferred equity | 4 | No | Dividends | Limited | Perpetual | N/A |
| Common equity | 5 | No | Residual | Full | Perpetual | N/A |

### How to Use This Matrix

| Step | Action |
|---|---|
| **1** | Identify all capital instruments. |
| **2** | Determine the seniority rank of each. |
| **3** | Determine the security status of each. |
| **4** | Determine the return type of each. |
| **5** | Determine the control rights of each. |
| **6** | Determine the maturity of each. |
| **7** | Assess refinancing risk. |
| **8** | Document the matrix in capital documents. |
| **9** | Review and update the matrix periodically. |

---

## 9. Implementation Sequence

### Step 1: Define Capital Philosophy

**What is it?**

Defining the capital philosophy means answering the fundamental questions: **What is the institution's approach to financing?** Is it conservative, aggressive, or balanced? Does it prioritize growth, control, or resilience?

**Why is this step important?**

Capital philosophy determines everything about capital structure design. Without a clear philosophy, capital structure is ad-hoc and fragile.

**How is it executed?**

| Action | Description |
|---|---|
| **Clarify objectives** | What does the institution want to achieve with its capital structure? |
| **Define risk tolerance** | What level of financial risk is acceptable? |
| **Define growth priorities** | How important is growth vs. control vs. resilience? |
| **Document philosophy** | Write a clear statement of capital philosophy. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Unclear philosophy** | Document the philosophy explicitly. |
| **Unrealistic preferences** | Align preferences with market realities. |
| **No buy-in** | Ensure all stakeholders agree on the philosophy. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead the philosophy definition. |
| **Board** | To approve the capital philosophy. |
| **Shareholders** | To align with the capital philosophy. |

---

### Step 2: Model Long-Term Cashflow Capacity

**What is it?**

Modeling long-term cashflow capacity means forecasting the institution's future cashflows to determine its debt service capacity.

**Why is this step important?**

Debt capacity is determined by cashflow. Without accurate cashflow modeling, the institution may take on too much or too little debt.

**How is it executed?**

| Action | Description |
|---|---|
| **Forecast revenues** | Project revenues over 5-10 years. |
| **Forecast costs** | Project costs over 5-10 years. |
| **Calculate EBITDA** | Calculate EBITDA over 5-10 years. |
| **Calculate DSCR** | Calculate Debt Service Coverage Ratio. |
| **Stress-test cashflows** | Stress-test cashflows against downside scenarios. |
| **Determine debt capacity** | Determine the maximum debt the institution can service. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Optimistic forecasts** | Use conservative assumptions. |
| **Ignoring stress scenarios** | Stress-test against downside scenarios. |
| **Inadequate modeling** | Use comprehensive financial modeling. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead cashflow modeling. |
| **Finance team** | To execute modeling. |
| **Board** | To review and approve forecasts. |

---

### Step 3: Determine Target Leverage Ratio

**What is it?**

Determining the target leverage ratio means deciding how much debt the institution will carry relative to its equity or EBITDA.

**Why is this step important?**

Leverage ratio is the most critical capital structure decision. It determines financial risk, cost of capital, and resilience.

**How is it executed?**

| Action | Description |
|---|---|
| **Review industry benchmarks** | What are typical leverage ratios in the industry? |
| **Assess risk tolerance** | What level of risk is acceptable? |
| **Determine target ratio** | Set a target leverage ratio (e.g., 3x EBITDA). |
| **Stress-test target** | Stress-test the target against downside scenarios. |
| **Document target** | Document the target leverage ratio. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Too aggressive** | Set conservative leverage targets. |
| **Too conservative** | Ensure leverage is sufficient for growth. |
| **Ignoring industry norms** | Consider industry benchmarks. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To recommend leverage targets. |
| **Board** | To approve leverage targets. |

---

### Step 4: Design Seniority Hierarchy

**What is it?**

Designing the seniority hierarchy means defining the priority order of claims in liquidation.

**Why is this step important?**

Seniority clarity is essential for bankability. Financiers must know their position in the capital stack.

**How is it executed?**

| Action | Description |
|---|---|
| **Identify instruments** | What capital instruments will be used? |
| **Define priority** | What is the priority order? |
| **Determine security** | Which instruments will be secured? |
| **Document hierarchy** | Create a capital priority matrix. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Ambiguous priority** | Define priority explicitly. |
| **Overly complex hierarchy** | Keep the hierarchy as simple as possible. |
| **Inconsistent documentation** | Ensure all documents reflect the hierarchy. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To design the seniority hierarchy. |
| **Legal Counsel** | To draft intercreditor and subordination agreements. |
| **Board** | To approve the hierarchy. |

---

### Step 5: Define Equity Dilution Thresholds

**What is it?**

Defining equity dilution thresholds means setting limits on how much equity can be issued and under what conditions, to protect existing shareholders from excessive dilution.

**Why is this step important?**

Excessive dilution shocks shareholders, creates conflict, and can destabilize the institution.

**How is it executed?**

| Action | Description |
|---|---|
| **Define dilution cap** | What is the maximum acceptable dilution? |
| **Define preemptive rights** | Existing shareholders' rights to participate in new issuances. |
| **Define anti-dilution provisions** | Protections against dilution. |
| **Document thresholds** | Document dilution thresholds in capital documents. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Too restrictive** | Ensure dilution thresholds allow necessary financing. |
| **Too permissive** | Ensure existing shareholders are protected. |
| **Undocumented** | Document thresholds clearly. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To propose dilution thresholds. |
| **Board** | To approve dilution thresholds. |
| **Shareholders** | To approve significant issuances. |

---

### Step 6: Structure Covenant Framework

**What is it?**

Structuring the covenant framework means defining the covenants attached to debt instruments.

**Why is this step important?**

Covenants protect lenders but can constrain operations. The framework must balance lender protection with operational flexibility.

**How is it executed?**

| Action | Description |
|---|---|
| **Identify required covenants** | What covenants are required by lenders? |
| **Define covenant levels** | What are the covenant thresholds? |
| **Define headroom** | What is the headroom for underperformance? |
| **Define cure periods** | How long does the institution have to cure a breach? |
| **Document covenants** | Document covenants in debt agreements. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Too restrictive** | Ensure covenants allow operational flexibility. |
| **Too permissive** | Ensure covenants provide adequate lender protection. |
| **Insufficient headroom** | Provide adequate headroom for stress scenarios. |
| **No cure periods** | Include cure periods for breaches. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To negotiate covenant terms. |
| **Treasury** | To monitor covenant compliance. |
| **Legal Counsel** | To draft covenant provisions. |
| **Board** | To approve covenant terms. |

---

### Step 7: Align Tenor with Asset Life

**What is it?**

Aligning tenor with asset life means ensuring that the duration of capital matches the life of the assets being financed.

**Why is this step important?**

Tenor mismatch creates rollover risk, which can lead to refinancing failure and default.

**How is it executed?**

| Action | Description |
|---|---|
| **Determine asset life** | What is the life of the assets being financed? |
| **Determine capital tenor** | What is the tenor of the capital? |
| **Match tenor** | Ensure capital tenor matches asset life. |
| **Plan for mismatch** | If mismatch exists, develop a refinancing plan. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Ignoring asset life** | Match tenor with asset life. |
| **Assuming easy refinancing** | Plan for refinancing risk. |
| **No plan** | Develop a refinancing plan. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To ensure tenor matching. |
| **Treasury** | To structure financing. |
| **Board** | To approve financing strategies. |

---

### Step 8: Model Stress-Case Servicing Ability

**What is it?**

Modeling stress-case servicing ability means assessing whether the institution can service its debt under downside scenarios.

**Why is this step important?**

Stress-case modeling reveals vulnerabilities. If the institution cannot service debt under stress, it is over-leveraged.

**How is it executed?**

| Action | Description |
|---|---|
| **Define stress scenarios** | What are the potential downside scenarios? |
| **Model cashflows** | Model cashflows under each scenario. |
| **Calculate DSCR** | Calculate Debt Service Coverage Ratio under each scenario. |
| **Assess resilience** | Can the institution service debt under each scenario? |
| **Adjust leverage** | If not, reduce leverage. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Insufficient scenarios** | Include a comprehensive range of scenarios. |
| **Optimistic assumptions** | Use conservative assumptions. |
| **Ignoring results** | Act on stress-test results. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead stress-case modeling. |
| **Finance team** | To execute modeling. |
| **Board** | To review and approve stress-test results. |

---

### Step 9: Validate Tax Implications

**What is it?**

Validating tax implications means assessing the tax treatment of the capital structure, including interest deductibility, withholding taxes, and other tax considerations.

**Why is this step important?**

Tax treatment affects the after-tax cost of capital. Improper tax planning can erode value.

**How is it executed?**

| Action | Description |
|---|---|
| **Assess interest deductibility** | Is interest deductible? |
| **Assess withholding taxes** | Are there withholding taxes on cross-border payments? |
| **Assess transfer pricing** | Is there transfer pricing risk? |
| **Assess tax treaty benefits** | Are tax treaty benefits available? |
| **Document tax analysis** | Document the tax analysis. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Ignoring tax** | Include tax in capital structure design. |
| **Aggressive tax planning** | Ensure tax planning is defensible. |
| **Insufficient documentation** | Document tax analysis thoroughly. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead tax analysis. |
| **Tax Advisor** | To provide tax advice. |
| **Tax Structure (Chapter 7)** | To optimize tax position. |

---

### Step 10: Negotiate Intercreditor Alignment

**What is it?**

Negotiating intercreditor alignment means ensuring that all lenders agree on the priority of their claims and the terms of their relationships.

**Why is this step important?**

Intercreditor disputes are common and destructive. Clear intercreditor agreements prevent disputes.

**How is it executed?**

| Action | Description |
|---|---|
| **Identify lenders** | Who are all the lenders? |
| **Define priority** | What is the priority of each lender? |
| **Define rights** | What are the rights of each lender? |
| **Define remedies** | What are the remedies in default? |
| **Draft intercreditor agreement** | Draft an intercreditor agreement. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Ambiguous priority** | Define priority explicitly. |
| **Incomplete agreement** | Include all lenders and all issues. |
| **Unilateral agreements** | Ensure all lenders agree. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead intercreditor negotiations. |
| **Legal Counsel** | To draft intercreditor agreements. |
| **Lenders** | To agree to intercreditor terms. |

---

### Step 11: Stress-Test Refinancing Scenario

**What is it?**

Stress-testing the refinancing scenario means assessing whether the institution can refinance its debt when it matures.

**Why is this step important?**

Refinancing failure is a common cause of institutional failure. Stress-testing reveals refinancing vulnerabilities.

**How is it executed?**

| Action | Description |
|---|---|
| **Map maturities** | When does each debt mature? |
| **Assess refinancing capacity** | Can the institution refinance at maturity? |
| **Assess market conditions** | What if market conditions are unfavorable? |
| **Identify vulnerabilities** | Where are the refinancing risks? |
| **Develop contingency plan** | Develop a contingency refinancing plan. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Assuming easy refinancing** | Stress-test under adverse market conditions. |
| **Ignoring maturity walls** | Stagger maturities. |
| **No contingency plan** | Develop a contingency plan. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To lead refinancing stress-testing. |
| **Treasury** | To execute refinancing planning. |
| **Board** | To approve refinancing strategies. |

---

### Step 12: Obtain Governance Approval

**What is it?**

Obtaining governance approval means securing board and, where required, shareholder approval for the capital structure.

**Why is this step important?**

Capital structure decisions are material. They require governance approval to ensure legitimacy and accountability.

**How is it executed?**

| Action | Description |
|---|---|
| **Prepare proposal** | Prepare a capital structure proposal. |
| **Present to board** | Present the proposal to the board. |
| **Obtain board approval** | Obtain board approval. |
| **Obtain shareholder approval** | Obtain shareholder approval if required. |
| **Document approvals** | Document all approvals. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Insufficient preparation** | Prepare a comprehensive proposal. |
| **No buy-in** | Ensure board and shareholder buy-in. |
| **Unapproved actions** | Obtain approval before executing. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To prepare the proposal. |
| **Board** | To approve the proposal. |
| **Shareholders** | To approve if required. |

---

### Step 13: Execute Documentation

**What is it?**

Executing documentation means signing and filing all capital structure documents.

**Why is this step important?**

Undocumented capital structure is unenforceable. Documentation is the foundation of institutional-grade capital structure.

**How is it executed?**

| Action | Description |
|---|---|
| **Draft all documents** | Draft all required capital documents. |
| **Execute documents** | Sign all documents. |
| **File documents** | File documents with relevant authorities. |
| **Store documents** | Store documents securely. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Missing documents** | Use a documentation checklist. |
| **Unfiled documents** | File documents promptly. |
| **Insecure storage** | Use secure storage. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To oversee documentation. |
| **Legal Counsel** | To ensure document completeness. |
| **Company Secretary** | To maintain documentation. |

---

### Step 14: Register Security and Filings

**What is it?**

Registering security and filings means perfecting security interests and making required filings.

**Why is this step important?**

Unregistered security is unenforceable. Registration is required for effective security.

**How is it executed?**

| Action | Description |
|---|---|
| **Identify security interests** | What security interests exist? |
| **File registrations** | File security registrations with relevant authorities. |
| **Perfect security** | Perfect all security interests. |
| **Document filings** | Document all filings. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Unregistered security** | Register all security interests. |
| **Incomplete filings** | Ensure all filings are complete. |
| **No documentation** | Document all filings. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To lead registration and filings. |
| **CFO** | To oversee security registration. |
| **Company Secretary** | To maintain documentation. |

---

### Step 15: Establish Monitoring Dashboard

**What is it?**

Establishing a monitoring dashboard means creating a system for tracking capital structure metrics and covenant compliance.

**Why is this step important?**

Capital structure must be monitored continuously. Early warning of issues enables remediation before they become crises.

**How is it executed?**

| Action | Description |
|---|---|
| **Define KPIs** | What are the key capital structure metrics? |
| **Define reporting frequency** | How often will metrics be reported? |
| **Define escalation triggers** | What triggers escalation? |
| **Build dashboard** | Build a monitoring dashboard. |
| **Assign ownership** | Who is responsible for monitoring? |
| **Document system** | Document the monitoring system. |

**What are the common pitfalls?**

| Pitfall | Avoidance Strategy |
|---|---|
| **Insufficient metrics** | Include all critical metrics. |
| **Infrequent reporting** | Report frequently. |
| **No escalation** | Define escalation triggers. |
| **No ownership** | Assign ownership for monitoring. |

**Who is responsible?**

| Role | Responsibility |
|---|---|
| **CFO** | To oversee monitoring. |
| **Treasury** | To execute monitoring. |
| **Information & Transparency (Chapter 9)** | To build the dashboard. |

---

## 10. Stress Testing Framework

### Test 1: 30% Revenue Drop

**What is this test?**

This test simulates a 30% drop in revenue, assessing whether the capital structure can withstand a significant revenue shock.

**Why is this test relevant?**

Revenue drops are common in economic downturns. If the institution cannot service debt after a 30% revenue drop, it is over-leveraged.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Leverage resilience** | Can the institution service debt after a revenue drop? |
| **Covenant headroom** | Will covenants be breached? |
| **Liquidity** | Does the institution have liquidity to survive the shock? |
| **Refinancing risk** | Will the institution need to refinance under stress? |

**How is the test conducted?**

1. Reduce revenues by 30%.
2. Model the impact on EBITDA.
3. Calculate DSCR under stress.
4. Assess covenant compliance.
5. Assess liquidity position.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **DSCR > 1.5x** | Debt service coverage remains above 1.5x. |
| **Covenant headroom** | Covenants are not breached. |
| **Liquidity buffer** | Liquidity remains above minimum. |
| **Refinancing capacity** | Refinancing remains possible. |

---

### Test 2: 200 bps Interest Rate Increase

**What is this test?**

This test simulates a 200 basis point increase in interest rates, assessing whether the capital structure can withstand an interest rate shock.

**Why is this test relevant?**

Interest rate increases are a common macroeconomic shock. If the institution cannot service debt after a rate increase, it is vulnerable.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Interest rate sensitivity** | How sensitive is the institution to rate changes? |
| **Hedging effectiveness** | Are hedges effective? |
| **DSCR resilience** | Can DSCR withstand a rate increase? |
| **Covenant headroom** | Will covenants be breached? |

**How is the test conducted?**

1. Increase interest rates by 200 bps.
2. Model the impact on debt service.
3. Calculate DSCR under stress.
4. Assess covenant compliance.
5. Assess hedging effectiveness.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **DSCR > 1.5x** | Debt service coverage remains above 1.5x. |
| **Covenant headroom** | Covenants are not breached. |
| **Hedging effective** | Hedges protect against rate increases. |

---

### Test 3: Currency Devaluation

**What is this test?**

This test simulates a 20% currency devaluation, assessing whether the capital structure can withstand a currency shock.

**Why is this test relevant?**

Currency devaluations are common in emerging markets. If the institution has foreign currency debt, a devaluation can be catastrophic.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Currency exposure** | Does the institution have foreign currency debt? |
| **Hedging effectiveness** | Are hedges effective? |
| **DSCR resilience** | Can DSCR withstand a devaluation? |
| **Covenant headroom** | Will covenants be breached? |

**How is the test conducted?**

1. Devalue the currency by 20%.
2. Model the impact on debt service.
3. Calculate DSCR under stress.
4. Assess covenant compliance.
5. Assess hedging effectiveness.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **No significant exposure** | Foreign currency debt is limited or hedged. |
| **DSCR > 1.5x** | Debt service coverage remains above 1.5x. |
| **Hedging effective** | Hedges protect against currency risk. |

---

### Test 4: Refinancing Market Freeze

**What is this test?**

This test simulates a refinancing market freeze, assessing whether the capital structure can survive without refinancing.

**Why is this test relevant?**

Refinancing market freezes occurred in 2008 and other crises. If the institution cannot refinance, it defaults.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Refinancing dependency** | How dependent is the institution on refinancing? |
| **Maturity profile** | Are there maturity walls? |
| **Liquidity** | Does the institution have liquidity to survive without refinancing? |
| **Contingency financing** | Are there contingency financing sources? |

**How is the test conducted?**

1. Assume the refinancing market is frozen.
2. Map all debt maturities.
3. Assess the ability to repay maturing debt.
4. Assess liquidity position.
5. Assess contingency financing availability.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Staggered maturities** | Maturities are staggered, not concentrated. |
| **Liquidity buffer** | Liquidity is sufficient to cover maturities. |
| **Contingency financing** | Contingency financing is available. |

---

### Test 5: Covenant Breach Scenario

**What is this test?**

This test simulates a covenant breach scenario, assessing whether the capital structure can survive a covenant breach.

**Why is this test relevant?**

Covenant breaches are common and can trigger cross-defaults and acceleration.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Covenant headroom** | Is there adequate headroom? |
| **Cure periods** | Are there cure periods? |
| **Cross-default provisions** | Are there cross-default provisions? |
| **Lender relationships** | Are lender relationships strong? |

**How is the test conducted?**

1. Simulate a covenant breach.
2. Assess whether covenants were breached.
3. Assess cure periods.
4. Assess cross-default provisions.
5. Assess lender relationships.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Adequate headroom** | Covenants have adequate headroom. |
| **Cure periods** | Cure periods exist and are adequate. |
| **No cross-default** | Cross-default provisions are limited. |
| **Strong relationships** | Lender relationships are strong. |

---

### Test 6: Delayed Receivables

**What is this test?**

This test simulates a scenario where receivables are delayed by 90 days, assessing whether the capital structure can withstand a working capital shock.

**Why is this test relevant?**

Receivables delays are common in economic downturns. If the institution cannot maintain liquidity, it defaults.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Working capital resilience** | Can the institution survive receivable delays? |
| **Liquidity** | Does the institution have liquidity? |
| **Debt service** | Can debt service be maintained? |
| **Credit facility** | Is there a credit facility to cover delays? |

**How is the test conducted?**

1. Delay receivables by 90 days.
2. Model the impact on cashflow.
3. Assess liquidity position.
4. Assess debt service capacity.
5. Assess credit facility availability.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Liquidity buffer** | Liquidity is sufficient to cover delays. |
| **Debt service** | Debt service can be maintained. |
| **Credit facility** | A credit facility is available. |

---

### Test 7: Litigation Shock

**What is this test?**

This test simulates a litigation shock—a large legal judgment or settlement—assessing whether the capital structure can withstand the financial impact.

**Why is this test relevant?**

Litigation shocks can be catastrophic. If the institution cannot absorb the cost, it defaults.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Litigation exposure** | Is there litigation exposure? |
| **Capital absorption** | Can the capital structure absorb the shock? |
| **Liquidity** | Does the institution have liquidity? |
| **Insurance** | Is there insurance coverage? |

**How is the test conducted?**

1. Simulate a large litigation judgment.
2. Model the impact on cashflow and balance sheet.
3. Assess capital absorption capacity.
4. Assess liquidity position.
5. Assess insurance coverage.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Capital absorption** | The capital structure can absorb the shock. |
| **Liquidity** | Liquidity is sufficient. |
| **Insurance** | Insurance covers the litigation. |

---

### Test 8: Asset Impairment

**What is this test?**

This test simulates an asset impairment event, assessing whether the capital structure can withstand a write-down of asset values.

**Why is this test relevant?**

Asset impairments can trigger covenant breaches and reduce collateral values.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Asset exposure** | Is there exposure to impaired assets? |
| **Collateral sufficiency** | Is collateral sufficient after impairment? |
| **Covenant headroom** | Will covenants be breached? |
| **Equity buffer** | Is there equity buffer? |

**How is the test conducted?**

1. Simulate an asset impairment.
2. Model the impact on the balance sheet.
3. Assess collateral sufficiency.
4. Assess covenant compliance.
5. Assess equity buffer.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Collateral sufficiency** | Collateral remains sufficient. |
| **Covenant headroom** | Covenants are not breached. |
| **Equity buffer** | Equity buffer is adequate. |

---

### Test 9: Credit Rating Downgrade

**What is this test?**

This test simulates a credit rating downgrade, assessing whether the capital structure can withstand the impact.

**Why is this test relevant?**

Credit rating downgrades can increase borrowing costs and trigger covenant breaches.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Rating sensitivity** | How sensitive is the institution to rating changes? |
| **Covenant triggers** | Are there rating-based covenants? |
| **Cost impact** | How much will borrowing costs increase? |
| **Refinancing risk** | Will refinancing become more difficult? |

**How is the test conducted?**

1. Simulate a credit rating downgrade.
2. Assess the impact on borrowing costs.
3. Assess covenant triggers.
4. Assess refinancing risk.
5. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Cost resilience** | The institution can absorb higher costs. |
| **No rating-based covenants** | Covenants are not rating-based. |
| **Refinancing capacity** | Refinancing remains possible. |

---

### Test 10: Exit at Sub-Target Valuation

**What is this test?**

This test simulates an exit at a sub-target valuation, assessing whether the capital structure can absorb the loss.

**Why is this test relevant?**

Exits at sub-target valuations are common in challenging markets. If the capital structure cannot absorb the loss, equity holders are wiped out.

**What does it reveal?**

| Insight | What It Reveals |
|---|---|
| **Liquidation preference impact** | How do preferences affect exit proceeds? |
| **Equity return** | What return do equity holders receive? |
| **Value distribution** | How is value distributed? |
| **Capital loss** | Who absorbs the loss? |

**How is the test conducted?**

1. Simulate an exit at 75% of target valuation.
2. Model the distribution of proceeds.
3. Assess liquidation preference impact.
4. Assess equity return.
5. Assess capital loss absorption.
6. Identify weaknesses and remediate.

**What constitutes a passing result?**

| Criteria | Passing Standard |
|---|---|
| **Equity return** | Equity holders receive a reasonable return. |
| **Capital loss absorption** | Losses are absorbed appropriately. |
| **No conflict** | Distribution does not create conflict. |

---

## 11. Institutional & Bankability Test

### What are institutional evaluators looking for?

Institutional evaluators—private equity firms, DFIs, commercial banks—evaluate capital structure based on:

| Criteria | What They Look For |
|---|---|
| **DSCR robustness** | Debt Service Coverage Ratio is robust under stress. |
| **Clear seniority ranking** | Seniority is clearly defined. |
| **Intercreditor clarity** | Intercreditor agreements are clear and enforceable. |
| **Collateral sufficiency** | Collateral is sufficient to secure debt. |
| **Covenant transparency** | Covenants are transparent and reasonable. |
| **Hedging strategy** | Hedging is in place for material risks. |
| **Liquidity reserves** | Liquidity reserves are adequate. |
| **Predictable refinancing pathway** | Refinancing is predictable. |
| **Capital stack transparency** | The capital stack is transparent. |
| **No hidden guarantees** | There are no hidden personal guarantees. |
| **ESG-linked financing alignment** | ESG considerations are integrated. |

### Why does this matter?

| Consequence | Description |
|---|---|
| **Capital access** | Strong capital structure enables access to institutional capital. |
| **Cost of capital** | Strong capital structure lowers the cost of capital. |
| **Valuation** | Strong capital structure increases valuation. |
| **Exit readiness** | Strong capital structure makes exit easier. |
| **Resilience** | Strong capital structure protects against financial shocks. |

### How is this assessed?

| Assessment Method | Description |
|---|---|
| **Due diligence** | Institutional investors conduct thorough due diligence on capital structure. |
| **Financial modeling** | Investors review financial models and stress-testing. |
| **Documentation review** | Investors review all capital documents. |
| **Interviews** | Investors interview management and advisors. |

### What are the financial implications?

| Scenario | Impact |
|---|---|
| **Strong capital structure** | Lower cost of capital, higher valuation, easier access to capital, easier exit. |
| **Weak capital structure** | Higher cost of capital, lower valuation, difficulty accessing capital, difficult exit. |

---

## 12. Red Flags

### Red Flag: Debt > Sustainable Cashflow

**What is it?**

The institution has more debt than its cashflow can sustain. Debt service consumes an excessive portion of cashflow.

**Why is it a red flag?**

Excessive debt leads to default when cashflow declines. The institution cannot service its debt.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **High leverage** | Leverage is above sustainable levels. |
| **Low DSCR** | Debt Service Coverage Ratio is below 1.5x. |
| **Cashflow strain** | Debt service consumes >30% of cashflow. |
| **High interest coverage** | Interest Coverage Ratio is low. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Default** | The institution defaults on debt. |
| **Forced restructuring** | The institution is forced into restructuring. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Financial analysis** | Analyze DSCR, leverage, and interest coverage. |
| **Stress-testing** | Stress-test debt service capacity. |
| **Comparative analysis** | Compare to industry benchmarks. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Reduce debt** | Pay down debt. |
| **Refinance** | Refinance to lower cost or longer tenor. |
| **Restructure** | Restructure debt. |
| **Increase cashflow** | Improve operational performance. |

---

### Red Flag: Bullet Maturity Concentration

**What is it?**

A large proportion of debt matures at the same time, creating a concentration of refinancing risk.

**Why is it a red flag?**

A maturity wall creates refinancing risk. If the institution cannot refinance, it defaults.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Concentrated maturities** | Multiple debts mature in the same year. |
| **Large refinancing need** | Refinancing need is >50% of debt. |
| **No refinancing plan** | There is no refinancing plan. |
| **Market dependency** | Refinancing is dependent on favorable market conditions. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Refinancing failure** | The institution cannot refinance. |
| **Default** | The institution defaults. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Maturity profile analysis** | Analyze maturity profile. |
| **Refinancing plan review** | Review refinancing plan. |
| **Market assessment** | Assess refinancing market conditions. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Stagger maturities** | Stagger maturities to avoid concentration. |
| **Refinance early** | Refinance early to spread maturities. |
| **Secure contingency** | Secure contingency financing. |

---

### Red Flag: Unhedged Floating-Rate Exposure

**What is it?**

The institution has floating-rate debt but has not hedged the interest rate risk.

**Why is it a red flag?**

Unhedged floating-rate exposure creates interest rate risk. If rates rise, debt service becomes more expensive.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Floating-rate debt** | Debt has floating rates. |
| **No hedges** | Interest rate hedges are not in place. |
| **Rate sensitivity** | The institution is sensitive to rate increases. |
| **No hedging policy** | There is no hedging policy. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Increased debt service** | Debt service increases with rates. |
| **Default** | The institution cannot service debt. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Hedge review** | Review hedging instruments. |
| **Rate sensitivity analysis** | Analyze sensitivity to rate changes. |
| **Policy review** | Review hedging policy. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Hedge floating-rate exposure** | Enter into interest rate swaps or caps. |
| **Convert to fixed rate** | Refinance to fixed-rate debt. |
| **Establish hedging policy** | Establish a formal hedging policy. |

---

### Red Flag: Cross-Default Across Subsidiaries

**What is it?**

Cross-default provisions across subsidiaries mean that a default in one subsidiary triggers defaults in others.

**Why is it a red flag?**

Cross-default creates contagion risk. A problem in one subsidiary spreads to others.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Cross-default provisions** | Debt agreements include cross-default provisions. |
| **Subsidiary debt** | Subsidiaries have debt with cross-default provisions. |
| **No isolation** | Debt is not isolated to individual subsidiaries. |
| **Cascade risk** | A default in one subsidiary triggers defaults in others. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Contagion** | Problems spread across subsidiaries. |
| **Cascade** | All debt becomes due. |
| **Default** | The institution defaults on all debt. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Covenant review** | Review all covenants for cross-default provisions. |
| **Subsidiary analysis** | Analyze subsidiary debt structures. |
| **Legal review** | Review legal documents for cross-default. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Negotiate limitations** | Negotiate limitations on cross-default provisions. |
| **Isolate debt** | Isolate debt to individual subsidiaries. |
| **Covenant headroom** | Maintain headroom to avoid breaches. |

---

### Red Flag: Personal Guarantees for Corporate Debt

**What is it?**

Founders or shareholders have provided personal guarantees for the institution's debt.

**Why is it a red flag?**

Personal guarantees create personal risk. If the institution defaults, the guarantor loses personal assets.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Personal guarantees** | Founders or shareholders have personal guarantees. |
| **No limit** | Guarantees are unlimited. |
| **No insurance** | Guarantees are not insured. |
| **No disclosure** | Guarantees are not disclosed. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Personal asset loss** | Guarantors lose personal assets. |
| **Personal bankruptcy** | Guarantors file for personal bankruptcy. |
| **Institutional instability** | Guarantor loss destabilizes the institution. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Guarantee review** | Review all guarantees. |
| **Interviews** | Interview founders and shareholders. |
| **Legal review** | Review legal documents for guarantees. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Remove guarantees** | Remove personal guarantees. |
| **Limit guarantees** | Limit guarantees to specific amounts. |
| **Insure guarantees** | Insure guarantee risk. |
| **Substitute collateral** | Use corporate assets as collateral. |

---

### Red Flag: Ambiguous Subordination

**What is it?**

Subordination of claims is ambiguous—it is unclear which debt is senior and which is junior.

**Why is it a red flag?**

Ambiguous subordination creates intercreditor disputes in default. Lenders will argue about priority.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **No subordination agreement** | There is no subordination agreement. |
| **Ambiguous language** | Subordination language is ambiguous. |
| **Overlapping claims** | Claims overlap in priority. |
| **No intercreditor agreement** | There is no intercreditor agreement. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Intercreditor dispute** | Lenders dispute priority. |
| **Litigation** | Lenders sue each other. |
| **Value destruction** | Value is destroyed. |
| **Delayed resolution** | Default is not resolved quickly. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Document review** | Review subordination and intercreditor documents. |
| **Legal review** | Review legal documents for priority clarity. |
| **Interviews** | Interview lenders and advisors. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Draft subordination agreement** | Draft a clear subordination agreement. |
| **Draft intercreditor agreement** | Draft a clear intercreditor agreement. |
| **Clarify priority** | Clarify claim priority explicitly. |

---

### Red Flag: Excessive Liquidation Preference Stacking

**What is it?**

Multiple layers of liquidation preferences (multiple investors with preferences) create a complex preference stack.

**Why is it a red flag?**

Excessive preferences create distortions. Equity holders may not receive returns if preferences consume all proceeds.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Multiple preferences** | Multiple investors have liquidation preferences. |
| **High preference amounts** | Preferences exceed equity value. |
| **Participation rights** | Preferences include participation rights. |
| **Complexity** | The preference stack is complex. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Equity wipeout** | Equity holders receive nothing. |
| **Distorted incentives** | Preferences create perverse incentives. |
| **Conflict** | Investors conflict over preferences. |
| **Exit difficulty** | Exit becomes difficult due to preferences. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Preference review** | Review all liquidation preferences. |
| **Distribution modeling** | Model distribution of proceeds. |
| **Equity analysis** | Assess equity return. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Simplify preferences** | Simplify the preference stack. |
| **Reduce preferences** | Reduce preference amounts. |
| **Eliminate participation** | Eliminate participation rights. |

---

### Red Flag: Convertible Instruments Without Cap Modeling

**What is it?**

Convertible instruments exist but the impact of conversion has not been modeled—dilution is not understood.

**Why is it a red flag?**

Conversion creates unexpected dilution. If dilution is not modeled, existing shareholders are surprised.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Convertible instruments** | Convertible debt or equity exists. |
| **No dilution modeling** | Dilution has not been modeled. |
| **Unexpected conversion** | Conversion may be triggered unexpectedly. |
| **No disclosure** | Conversion terms are not disclosed. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Dilution shock** | Existing shareholders are diluted unexpectedly. |
| **Control loss** | Existing shareholders lose control. |
| **Conflict** | Shareholders challenge conversion. |
| **Litigation** | Shareholders sue over dilution. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Instrument review** | Review all convertible instruments. |
| **Dilution modeling** | Model dilution impact. |
| **Disclosure review** | Review disclosure of conversion terms. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Model dilution** | Model dilution impact and communicate. |
| **Disclose terms** | Disclose conversion terms clearly. |
| **Simplify instruments** | Simplify convertible instruments. |

---

### Red Flag: No Refinancing Plan

**What is it?**

There is no plan for refinancing maturing debt. The institution assumes refinancing will be available.

**Why is it a red flag?**

No refinancing plan creates refinancing risk. If refinancing is not available, the institution defaults.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **No refinancing plan** | There is no plan for refinancing. |
| **Concentrated maturities** | Maturities are concentrated. |
| **Market dependency** | Refinancing is dependent on favorable market conditions. |
| **No contingency** | There is no contingency financing. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Refinancing failure** | The institution cannot refinance. |
| **Default** | The institution defaults. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Plan review** | Review refinancing plan. |
| **Maturity analysis** | Analyze maturity profile. |
| **Market assessment** | Assess refinancing market conditions. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Develop refinancing plan** | Develop a comprehensive refinancing plan. |
| **Stagger maturities** | Stagger maturities. |
| **Secure contingency** | Secure contingency financing. |

---

### Red Flag: Equity Dilution Beyond Founder Survival Threshold

**What is it?**

Equity dilution has diluted founders beyond their survival threshold—they have lost control or meaningful economic participation.

**Why is it a red flag?**

Founder dilution beyond survival threshold creates founder disengagement, conflict, and instability.

**What are the warning signs?**

| Warning Sign | Description |
|---|---|
| **Significant dilution** | Founders have been significantly diluted. |
| **Loss of control** | Founders have lost control. |
| **Founder disengagement** | Founders are disengaged. |
| **Founder conflict** | Founders are in conflict with new investors. |

**What is the potential impact?**

| Impact | Description |
|---|---|
| **Founder disengagement** | Founders lose motivation. |
| **Founder departure** | Founders leave. |
| **Institutional instability** | Founders' departure destabilizes the institution. |
| **Value destruction** | Value is destroyed. |

**How is it detected?**

| Detection Method | Description |
|---|---|
| **Cap table review** | Review founder ownership. |
| **Founder interviews** | Interview founders. |
| **Dilution modeling** | Model dilution impact. |

**How is it corrected?**

| Correction Method | Description |
|---|---|
| **Limit dilution** | Limit future dilution. |
| **Founder equity** | Provide founder equity for value creation. |
| **Founder alignment** | Align founder incentives. |

---

## 13. Documentation Checklist

### Document: Loan Agreements

**What is it?**

The agreement between the borrower and lender governing the terms of the loan.

**What does it contain?**

| Content | Description |
|---|---|
| **Amount** | The amount of the loan. |
| **Interest rate** | The interest rate and terms. |
| **Maturity** | The maturity date. |
| **Covenants** | The covenants attached to the loan. |
| **Security** | The security for the loan. |
| **Events of default** | Events that constitute default. |

**Why is it required?**

Loan Agreements define the terms of debt financing. They are essential for institutional-grade capital structure.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Loan Agreements. |
| **Borrower** | To negotiate and execute Loan Agreements. |
| **Lender** | To approve Loan Agreements. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **Amendments** | Amendments may be required. |
| **Refinancing** | New agreements for refinancing. |

---

### Document: Credit Facility Agreements

**What is it?**

The agreement for a revolving credit facility.

**What does it contain?**

| Content | Description |
|---|---|
| **Facility amount** | The amount of the facility. |
| **Interest rate** | The interest rate and terms. |
| **Drawdown conditions** | Conditions for drawdown. |
| **Repayment** | Repayment terms. |
| **Covenants** | Covenants attached to the facility. |

**Why is it required?**

Credit Facility Agreements provide flexible working capital financing.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Credit Facility Agreements. |
| **Borrower** | To negotiate and execute Agreements. |
| **Lender** | To approve Agreements. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **Renewal** | Facilities are typically renewed annually. |
| **Amendments** | Amendments may be required. |

---

### Document: Intercreditor Agreements

**What is it?**

The agreement defining the priority and relationship among multiple lenders.

**What does it contain?**

| Content | Description |
|---|---|
| **Priority** | The priority of claims. |
| **Rights** | The rights of each lender. |
| **Remedies** | The remedies in default. |
| **Cooperation** | Cooperation provisions. |

**Why is it required?**

Intercreditor Agreements prevent disputes among lenders.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Intercreditor Agreements. |
| **Lenders** | To negotiate and execute Agreements. |
| **Borrower** | To facilitate Agreements. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New lenders** | When new lenders enter the capital structure. |
| **Amendments** | Amendments may be required. |

---

### Document: Subordination Agreements

**What is it?**

The agreement subordinating claims of junior debt to senior debt.

**What does it contain?**

| Content | Description |
|---|---|
| **Subordination** | The subordination of claims. |
| **Priority** | The priority of claims. |
| **Rights** | The rights of senior and junior lenders. |
| **Remedies** | The remedies in default. |

**Why is it required?**

Subordination Agreements clarify the priority of claims.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Subordination Agreements. |
| **Lenders** | To negotiate and execute Agreements. |
| **Borrower** | To facilitate Agreements. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New debt** | When new debt is added. |
| **Amendments** | Amendments may be required. |

---

### Document: Security Agreements

**What is it?**

The agreement securing debt with specific assets.

**What does it contain?**

| Content | Description |
|---|---|
| **Assets** | The assets securing the debt. |
| **Security interest** | The security interest granted. |
| **Conditions** | Conditions for enforcement. |
| **Remedies** | Remedies in default. |

**Why is it required?**

Security Agreements provide the legal basis for security.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Security Agreements. |
| **Borrower** | To grant security. |
| **Lender** | To accept security. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New debt** | When new debt is secured. |
| **Amendments** | Amendments may be required. |

---

### Document: Guarantee Agreements

**What is it?**

The agreement providing a guarantee of debt obligations.

**What does it contain?**

| Content | Description |
|---|---|
| **Guarantor** | The party providing the guarantee. |
| **Obligations** | The obligations guaranteed. |
| **Conditions** | Conditions for enforcement. |
| **Limits** | Limits on the guarantee. |

**Why is it required?**

Guarantee Agreements provide additional protection for lenders.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Guarantee Agreements. |
| **Guarantor** | To provide the guarantee. |
| **Lender** | To accept the guarantee. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New debt** | When new debt is guaranteed. |
| **Amendments** | Amendments may be required. |

---

### Document: Share Subscription Agreements

**What is it?**

The agreement under which investors subscribe to equity.

**What does it contain?**

| Content | Description |
|---|---|
| **Subscription amount** | The amount being invested. |
| **Share class** | The class of shares being subscribed. |
| **Price** | The price per share. |
| **Rights** | The rights attached to the shares. |
| **Conditions** | Conditions precedent. |

**Why is it required?**

Share Subscription Agreements evidence equity investments.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Subscription Agreements. |
| **Investors** | To negotiate and execute Agreements. |
| **Company** | To issue shares. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New investments** | Each new investment requires an agreement. |

---

### Document: Investor Rights Agreements

**What is it?**

The agreement defining investor rights, including governance, information, and exit rights.

**What does it contain?**

| Content | Description |
|---|---|
| **Governance rights** | Board representation and voting rights. |
| **Information rights** | Rights to information. |
| **Exit rights** | Drag-along, tag-along, and other exit rights. |
| **Preemptive rights** | Rights to participate in future issuances. |

**Why is it required?**

Investor Rights Agreements define the relationship between investors and the institution.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Investor Rights Agreements. |
| **Investors** | To negotiate and execute Agreements. |
| **Company** | To agree to rights. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New investors** | When new investors join. |
| **Amendments** | Amendments may be required. |

---

### Document: Convertible Note Agreements

**What is it?**

The agreement governing convertible notes.

**What does it contain?**

| Content | Description |
|---|---|
| **Principal** | The principal amount. |
| **Interest** | The interest rate and terms. |
| **Conversion terms** | The terms of conversion to equity. |
| **Maturity** | The maturity date. |
| **Events of default** | Events that constitute default. |

**Why is it required?**

Convertible Note Agreements govern convertible debt financing.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Convertible Note Agreements. |
| **Note holder** | To negotiate and execute Agreements. |
| **Company** | To issue notes. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New notes** | Each new issuance requires an agreement. |

---

### Document: Warrant Agreements

**What is it?**

The agreement governing warrants.

**What does it contain?**

| Content | Description |
|---|---|
| **Number of warrants** | The number of warrants. |
| **Exercise price** | The price to exercise warrants. |
| **Expiration** | The expiration date. |
| **Conditions** | Conditions for exercise. |

**Why is it required?**

Warrant Agreements govern warrants.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To draft Warrant Agreements. |
| **Warrantholder** | To negotiate and execute Agreements. |
| **Company** | To issue warrants. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New warrants** | Each new issuance requires an agreement. |

---

### Document: Hedging Contracts

**What is it?**

The contracts hedging interest rate, currency, or commodity risk.

**What does it contain?**

| Content | Description |
|---|---|
| **Hedged exposure** | The exposure being hedged. |
| **Hedge terms** | The terms of the hedge. |
| **Counterparty** | The counterparty to the hedge. |
| **Collateral** | Collateral requirements. |

**Why is it required?**

Hedging Contracts protect against financial risks.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Treasury** | To negotiate Hedging Contracts. |
| **Legal Counsel** | To draft Hedging Contracts. |
| **Counterparty** | To agree to contracts. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New hedges** | When new hedges are entered. |
| **Amendments** | Amendments may be required. |

---

### Document: Capitalization Table (Updated Post-Issuance)

**What is it?**

The capitalization table updated after each capital issuance.

**What does it contain?**

| Content | Description |
|---|---|
| **Shareholder name** | The name of each shareholder. |
| **Share class** | The class of shares held. |
| **Number of shares** | The number of shares held. |
| **Percentage ownership** | The percentage of total shares held. |
| **Date** | The date of the update. |

**Why is it required?**

The Capitalization Table is the single source of truth for ownership.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Company Secretary** | To maintain the Capitalization Table. |
| **CFO** | To review and approve updates. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **Each issuance** | After each share issuance. |
| **Each transfer** | After each share transfer. |

---

### Document: Board and Shareholder Approvals

**What is it?**

The approvals by the board and shareholders for capital actions.

**What does it contain?**

| Content | Description |
|---|---|
| **Approval date** | The date of approval. |
| **Approving body** | The body granting approval. |
| **Resolution** | The resolution approving the action. |
| **Signatures** | Signatures of approving parties. |

**Why is it required?**

Approvals provide evidence of governance authorization.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Company Secretary** | To document approvals. |
| **Board** | To grant approvals. |
| **Shareholders** | To grant approvals. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **Each capital action** | After each capital action requiring approval. |

---

### Document: Collateral Registry Filings

**What is it?**

Filings of security interests with relevant authorities.

**What does it contain?**

| Content | Description |
|---|---|
| **Security interest** | The security interest being filed. |
| **Secured party** | The party with the security interest. |
| **Debtor** | The debtor granting the security interest. |
| **Assets** | The assets secured. |
| **Date** | The date of filing. |

**Why is it required?**

Collateral Registry Filings perfect security interests.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Legal Counsel** | To make Collateral Registry Filings. |
| **Company Secretary** | To maintain filing records. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **New security** | When new security is granted. |
| **Amendments** | Amendments may be required. |

---

### Document: Financial Covenant Monitoring Reports

**What is it?**

Reports monitoring compliance with financial covenants.

**What does it contain?**

| Content | Description |
|---|---|
| **Covenant terms** | The terms of the covenants. |
| **Current status** | The current status against covenants. |
| **Headroom** | The headroom available. |
| **Issues** | Any issues or breaches. |

**Why is it required?**

Covenant Monitoring Reports provide early warning of covenant breaches.

**Who is responsible for producing it?**

| Role | Responsibility |
|---|---|
| **Treasury** | To prepare Monitoring Reports. |
| **CFO** | To review Monitoring Reports. |
| **Board** | To review Monitoring Reports. |

**How often is it updated?**

| Frequency | Reason |
|---|---|
| **Monthly/Quarterly** | Reports should be prepared regularly. |

---

## 14. MICOS Scorecard

### What is the purpose of this scorecard?

The MICOS Capital Structure Scorecard is a self-assessment tool for evaluating the maturity and durability of an institution's capital structure.

### How is it used?

| Step | Action |
|---|---|
| **1** | Complete the scorecard for each dimension. |
| **2** | Identify areas where the institution scores "No" or "Partial." |
| **3** | Prioritize remediation based on risk and impact. |
| **4** | Track progress over time. |
| **5** | Use the scorecard for due diligence and investor communication. |

### A. Structural Integrity

| Criterion | Question | Significance | "Yes" Means |
|---|---|---|---|
| **Seniority unambiguous** | Is seniority clearly defined? | Seniority ambiguity creates disputes. | A capital priority matrix is documented and approved. |
| **Covenants defined** | Are covenants clearly defined? | Covenants must be clear to be enforceable. | All covenants are documented in debt agreements. |
| **Intercreditor agreements executed** | Are intercreditor agreements executed? | Intercreditor agreements prevent lender disputes. | Intercreditor agreements are executed and filed. |
| **Dilution modeled pre-issuance** | Is dilution modeled before issuance? | Dilution modeling prevents dilution shocks. | Dilution is modeled and communicated before issuances. |

### B. Serviceability

| Criterion | Question | Significance | "Yes" Means |
|---|---|---|---|
| **DSCR stress-tested** | Is DSCR stress-tested? | DSCR must be robust under stress. | DSCR is stress-tested against downside scenarios. |
| **Liquidity reserve present** | Is a liquidity reserve in place? | Liquidity reserves prevent liquidity crises. | A liquidity reserve is maintained. |
| **Tenor matches asset life** | Does capital tenor match asset life? | Tenor mismatch creates rollover risk. | Capital tenor is aligned with asset life. |
| **No maturity cliff concentration** | Is there no maturity cliff? | Maturity cliffs create refinancing risk. | Maturities are staggered, not concentrated. |

### C. Flexibility & Optionality

| Criterion | Question | Significance | "Yes" Means |
|---|---|---|---|
| **Refinancing pathway defined** | Is a refinancing pathway defined? | Refinancing must be planned. | A refinancing plan is documented. |
| **Prepayment flexibility reasonable** | Is prepayment flexibility reasonable? | Prepayment penalties should be reasonable. | Prepayment terms are reasonable. |
| **No covenant suffocation** | Do covenants not suffocate operations? | Covenants must balance protection with flexibility. | Covenants allow operational flexibility. |
| **Convertible overhang controlled** | Is convertible overhang controlled? | Convertible instruments must be understood and managed. | Convertible instruments are modeled and disclosed. |

### D. Institutional Durability

| Criterion | Question | Significance | "Yes" Means |
|---|---|---|---|
| **Bankable under DFI/PE standards** | Is the capital structure bankable? | Bankability is essential for institutional capital. | The structure passes the bankability test. |
| **ESG financing alignment** | Is the capital structure ESG-aligned? | ESG alignment is increasingly important. | ESG-linked financing is considered. |
| **No hidden guarantees** | Are there no hidden personal guarantees? | Hidden guarantees create personal risk. | No personal guarantees exist. |
| **Transparent reporting system** | Is there a transparent reporting system? | Transparency is essential for governance. | A capital structure monitoring dashboard exists. |

### Maturity Rating

| Level | Description | What It Looks Like |
|---|---|---|
| **0 — Informal funding only** | Capital is informal and undocumented. | No formal capital structure. Ad hoc financing. |
| **1 — Basic equity + ad hoc debt** | Basic equity and ad hoc debt exist. | Equity is structured; debt is ad hoc. No formal capital structure. |
| **2 — Structured but fragile** | Capital structure is structured but fragile. | Formal capital structure exists but is not stress-tested. Covenants are tight. |
| **3 — Institutional capital stack** | An institutional capital stack exists. | Formal capital structure. Clear seniority. Covenants are balanced. |
| **4 — Stress-tested & refinance-ready** | The structure is stress-tested and refinance-ready. | Stress-testing is conducted. Refinancing is planned. |
| **5 — Multi-cycle resilient, capital-market ready** | The structure is multi-cycle resilient and capital-market ready. | Fully stress-tested. ESG-aligned. Transparent. Bankable. |

**Level 5 requires ≥90% affirmative score across all dimensions.**

---

## Chapter Conclusion

### Key Insights

| Insight | Description |
|---|---|
| **Capital structure is the financial skeleton** | It determines claim priority, cost of capital, and financial resilience. |
| **Leverage must be serviceable under stress** | Over-leverage is the most common cause of financial distress. |
| **Seniority must be unambiguous** | Seniority ambiguity creates disputes and destroys value. |
| **Maturities must be staggered** | Maturity walls create refinancing risk. |
| **Capital structure must be bankable** | Institutional capital providers evaluate capital structure rigorously. |

### Link to Next Chapter

With a clear, documented, and bankable capital structure in place, the institution is ready to design its legal structure (Chapter 4). Legal structure establishes the jurisdictional framework that validates ownership, governance, and capital.

---

## Chapter Addendum: Cross-References

| Reference | Chapter | Context |
|---|---|---|
| Ownership Structure | Chapter 1 | Economic rights clarity is required for capital design. |
| Governance Structure | Chapter 2 | Approval authority must be defined before capital can be raised. |
| Legal Structure | Chapter 4 | The institution must have legal capacity to issue capital instruments. |
| Cashflow & Revenue Structure | Chapter 5 | Debt servicing capacity depends on cashflow. |
| Risk & Guarantee Structure | Chapter 6 | Default exposure depends on leverage. |
| Tax Structure | Chapter 7 | Interest deductibility and withholding depend on capital structure. |
| Incentive Structure | Chapter 12 | Equity dilution impacts incentive design. |
| Optionality & Exit Structure | Chapter 15 | Exit outcomes depend on capital structure. |
| Adaptive System | Chapters 16-20 | Strategic financing flexibility depends on capital structure. |
| Legacy System | Chapters 21-25 | Long-term solvency depends on capital structure. |

---

## Chapter Addendum: Case Study References

| Case Study | Reference | Context |
|---|---|---|
| *The Over-Leveraged Expansion* | Section 4 | Over-leverage failure mode. |
| *The Cross-Default Trap* | Section 4 | Cross-default failure mode. |
| *The Maturity Wall* | Section 4 | Maturity wall failure mode. |
| *The Mismatched Tenor* | Section 4 | Tenor mismatch failure mode. |
| *The Inefficient Capital Mix* | Section 4 | Excessive cost of capital. |
| *The Personal Guarantee Trap* | Section 4 | Hidden personal guarantees. |
| *The Dilution Shock* | Section 4 | Equity dilution shock. |
| *The Refinancing Failure* | Section 4 | Inability to refinance. |
| *The Currency Crisis* | Section 4 | Currency mismatch. |
| *The Over-Pledged Assets* | Section 4 | Collateral over-pledging. |

---

## Phase 2 Completion Checklist (Chapter 3)

| Step | Status |
|---|---|
| 2.1 Write the Chapter Introduction | ☐ |
| 2.2 Expand the "Strategic Function" | ☐ |
| 2.3 Expand the "Scope Boundary" | ☐ |
| 2.4 Write the Dependency Section | ☐ |
| 2.5 Expand the "Failure Modes" | ☐ |
| 2.6 Expand the "Design Principles" | ☐ |
| 2.7 Expand the "Architecture Patterns" | ☐ |
| 2.8 Expand the "Capital Priority Matrix" | ☐ |
| 2.9 Expand the "Implementation Sequence" | ☐ |
| 2.10 Expand the "Stress Testing Framework" | ☐ |
| 2.11 Expand the "Bankability & Institutional Test" | ☐ |
| 2.12 Expand the "Red Flags" | ☐ |
| 2.13 Expand the "Documentation Checklist" | ☐ |
| 2.14 Expand the "MICOS Scorecard" | ☐ |

---
