# AI System Inventory Template

A simple spreadsheet for keeping track of every AI system your company uses.

You can't manage AI you don't know about. This template gives you one place to list each system, say who owns it, rate how risky it is, and set when it gets checked again.

## What's in the file

**Read Me and Method.** A short guide on what the template is and how to use it.

**AI System Inventory.** The main list. One row per AI system. It has 22 columns, grouped into:

- **Identity:** ID, name, what it does, business owner, technical owner, lifecycle stage
- **Nature of the AI:** type of AI, autonomy, and any agentic abilities
- **Data:** how sensitive the data is, where the model came from, where the data comes from
- **Risk:** EU AI Act tier, whether it affects people's rights, internal risk tier, human oversight
- **Governance:** NIST AI RMF function, ISO 42001 Annex A reference, impact assessment status, vendor involved
- **Lifecycle:** review schedule and notes

**Field Reference.** Explains every column and every dropdown choice in plain words.

## What makes it different

**1. Autonomy.** Most inventories only say what kind of AI a system is. This one asks what the AI does. Does it only give advice and let a person decide? Or does it take action on its own? Each system goes on a scale:

Informs, Recommends, Acts with approval, Acts autonomously

The systems that act on their own need the closest watching, and this column helps you find them.

**2. Two risk ratings.** The EU AI Act tier is what the law says. The internal risk tier is your own view of how much could go wrong. They can be different. One of the examples is rated minimal risk by the EU but high risk internally, because it acts on its own and a mistake can spread fast.

## How to use it

1. Open the **AI System Inventory** tab.
2. Delete the three grey example rows (SYS-001 to SYS-003).
3. Add one row for each AI system you use. Use the dropdowns where you see them.
4. Check the **Field Reference** tab if you're not sure what a column means.
5. Set a review schedule for each system, and recheck it whenever something big changes (new data, more autonomy, a new use).

## Frameworks it lines up with

- NIST AI Risk Management Framework (Govern, Map, Measure, Manage)
- ISO/IEC 42001 (Annex A controls)
- EU AI Act (risk tiers)

## Note

The three example systems (CreditSense, HelpDesk Copilot, OpsPilot) are made up. They're only there to show you how to fill it in. This template does not contain any real company data.

## Author

Johnbosco Ibeneme
AI Governance and GRC

## License

Free to use and adapt. Please keep the author credit.
