# Attorney Analysis: Improvements for Law 1 (DoJ/FBI Forced Disclosure Act)

**Analyst Role:** Attorney reviewing proposed federal legislation
**Focus:** `1_DoJ_FBI/Law_1_DoJ_FBI.md`
**Date:** March 10, 2026

Sorted by importance -- most critical issues first.

---

## 1. Missing Congressional Findings Section (Constitutional Vulnerability)

**Problem:** The law has no section containing Congressional findings of fact or a constitutional basis for the legislation. This is the single most important missing element.

**Why it matters:** Courts apply rational basis review to legislation and look to congressional findings to determine whether Congress had a legitimate basis for acting. Without findings, the law is vulnerable to challenge on Commerce Clause, Spending Clause, or general separation-of-powers grounds. The Epstein Files Transparency Act and the JFK Records Act both included findings sections. A court reviewing this law will ask: "What constitutional authority supports this?" and the law provides no answer.

**Fix:** Add a new "Section 0: Congressional Findings" before the current Section 1, establishing: (a) the constitutional basis (Article I oversight power, Spending Clause for state/local cooperation, Commerce Clause for financial records); (b) factual findings about the inadequacy of existing investigations; (c) findings about prior disclosure law failures (Epstein Act, JFK Act); (d) the public interest in transparency. This was explicitly recommended in `Output_Analysis.md` Recommendation #1 and has not been implemented.

**Affects:** New section to add before Section 1.

---

## 2. Severability Clause is Entirely Missing

**Problem:** There is no severability provision anywhere in the law.

**Why it matters:** If any single provision is struck down by a court (e.g., the no-presidential-override clause, or a specific Schedule A item), the entire law could fall. A severability clause ensures that if one provision is held unconstitutional, the remainder survives. This is standard in virtually all federal legislation.

**Fix:** Add a new Section 14: *"If any provision of this Act, or the application thereof to any person or circumstance, is held invalid, the remainder of the Act and the application of such provision to other persons or circumstances shall not be affected thereby."*

**Affects:** New section needed.

---

## 3. No Presidential Override Clause -- Constitutional Infirmity (Section 11)

**Problem:** Section 11 attempts to strip the President of all authority to withhold records, including executive privilege. While the intent is sound (preventing JFK Act-style delays), an absolute prohibition on executive privilege may be unconstitutional under the separation of powers doctrine.

**Why it matters:** The Supreme Court in *United States v. Nixon* (1974) and *Trump v. Mazars USA* (2020) recognized a constitutionally grounded executive privilege. Congress can overcome it in specific cases with adequate justification, but a blanket prohibition stating "No executive order... may suspend, modify, or override" this Act could be struck down -- and without a severability clause, it takes the whole law with it.

**Fix:** Rewrite Section 11 to: (a) state that executive privilege is overcome by the compelling public interest in disclosure as found by Congress; (b) prohibit the President from unilaterally delaying disclosure beyond the statutory deadline; (c) require any assertion of executive privilege to be reviewed by the independent review board and a federal court within 14 days; (d) create a presumption against privilege. This preserves the intent while surviving constitutional challenge.

**Affects:** Section 11.

---

## 4. Item Count Inconsistencies Throughout the Document

**Problem:** The Purpose section says "207 specific disclosure items." Section 1(b)(1) says "205 Critical Disclosure Items." Section 3(b) says "205 Critical Disclosure Items." Section 10(a)(4) says "205 items." The Schedule A heading says "207 Critical Disclosure Items." The table of contents goes up to items #206-#207. The Notes file and Output_Analysis reference "175 items." The Human_Requirements file doesn't specify a count.

**Why it matters:** Inconsistent item counts create ambiguity that agencies will exploit. DOJ could argue it complied with "205 items" while ignoring items #206-#207, citing the internal inconsistency. Courts construe ambiguities in disclosure statutes against the party seeking disclosure.

**Fix:** Do a comprehensive count of actual Schedule A items. Update ALL references throughout the document (Purpose, Section 1(b)(1), Section 3(b), Section 10(a)(4), Schedule A heading) to the same correct number.

**Affects:** Purpose, Section 1(b)(1), Section 3(b), Section 10(a)(4), Schedule A heading.

---

## 5. Tenth Amendment Vulnerability in State/Local Cooperation (Section 12)

**Problem:** Section 12 conditions federal funding on state/local compliance, which is the correct Spending Clause approach, but it lacks the specificity the Supreme Court requires. It says "suspension of all federal law enforcement grants" without identifying which grants or giving states advance notice.

**Why it matters:** Under *South Dakota v. Dole* (1987) and *NFIB v. Sebelius* (2012), spending conditions must be: (a) related to the federal interest in the program; (b) unambiguous so states can knowingly accept; (c) not coercive. Suspending "all" federal grants is likely unconstitutionally coercive under *NFIB*.

**Fix:** (a) Specify which grants are subject to suspension (e.g., Byrne JAG grants, COPS grants -- directly related to law enforcement); (b) add a percentage cap (e.g., up to 10% of annual law enforcement grants); (c) require 30-day notice to the state before suspension takes effect; (d) provide a cure period.

**Affects:** Section 12.

---

## 6. Missing Special Master Provision

**Problem:** There is no mechanism for judicial appointment of a Special Master to compel compliance.

**Why it matters:** The Epstein Act's biggest compliance failure was the lack of a Special Master mechanism. Reps. Massie and Khanna had to request one after the fact with no statutory basis. The `Output_Analysis.md` Recommendation #2 explicitly calls for a Special Master provision, and it has not been implemented. Budget cuts and criminal penalties are blunt instruments; a Special Master provides ongoing, targeted judicial enforcement.

**Fix:** Add a provision (in Section 8 or as a new Section) authorizing any federal court to appoint a Special Master upon a finding of non-compliance, with authority to: (a) access agency systems; (b) compel production of specific records; (c) report directly to the court; (d) be funded by the non-compliant agency's budget.

**Affects:** Section 8 or new section.

---

## 7. Private Right of Action Too Broad (Section 9)

**Problem:** Section 9 allows "any citizen" to sue in federal court to "compel compliance" with no standing requirements, no exhaustion of administrative remedies, and no limits on venue.

**Why it matters:** DOJ will argue this violates Article III standing requirements (*Lujan v. Defenders of Wildlife*). Courts require concrete injury, not generalized grievances. Without guardrails, this provision invites dismissal on standing grounds and may generate frivolous litigation that creates bad precedent.

**Fix:** (a) Require 60-day notice to the agency and Attorney General before filing suit; (b) allow suits only after the 30-day disclosure deadline has passed; (c) specify that the injury is the denial of the statutory right to receive the disclosed records; (d) designate venue in the D.C. District Court to prevent forum shopping; (e) include a provision allowing courts to dismiss frivolous claims.

**Affects:** Section 9.

---

## 8. No Authorization of Appropriations

**Problem:** The law creates an independent review board (Section 8), requires forensic audits (Section 5(c)), mandates comprehensive searches (Section 2(d)), and implicitly requires significant resources, but includes no authorization of appropriations.

**Why it matters:** Without appropriated funds, the review board cannot hire staff, retain forensic auditors, or operate. Agencies will argue they lack resources to comply with the 30-day timeline. The review board becomes a paper entity.

**Fix:** Add a section authorizing appropriations: (a) for the independent review board's operations (suggest $5-10 million annually); (b) for agency compliance costs; (c) specify that funds shall be available immediately upon enactment and shall remain available until expended.

**Affects:** New section needed.

---

## 9. Review Board Appointment Mechanism is Vague (Section 8)

**Problem:** Section 8(a) says the board is "appointed by Congress (not the President)" but does not specify who nominates, which chamber appoints, qualifications, confirmation process, grounds for removal, or quorum requirements.

**Why it matters:** Vague appointment provisions create constitutional Appointments Clause problems (*Lucia v. SEC*, 2018). If board members exercise "significant authority," they may be "Officers of the United States" who must be appointed under Article II. Without clear procedures, political deadlock could prevent the board from ever being constituted.

**Fix:** Specify: (a) 2 members appointed by the Speaker of the House, 2 by the Senate Majority Leader, 1 by the Senate Minority Leader (or similar bipartisan formula); (b) members must have legal, forensic, or investigative expertise; (c) members serve for 4-year terms; (d) removal only for cause; (e) quorum of 3; (f) address the Appointments Clause by specifying the board has advisory and reporting functions (not adjudicatory), or provide for judicial appointment.

**Affects:** Section 8.

---

## 10. Records Preservation Trigger at "Bill Introduction" May Be Unenforceable (Section 5)

**Problem:** Section 5(a) says preservation requirements take effect "upon introduction of this bill" and Section 5(b) criminalizes destruction "after the date this bill is introduced." But a bill is not law until enacted. Congress cannot create criminal liability through a bill that has not been signed into law.

**Why it matters:** Criminal penalties under Section 5(b) cannot be enforced retroactively to the date of introduction -- that would be an ex post facto law (Article I, Section 9). However, upon enactment, Congress can legitimately require agencies to account for any destruction that occurred after introduction.

**Fix:** (a) Keep the trigger date at introduction for the preservation duty, but make it enforceable only upon enactment; (b) rewrite Section 5(b) to say: "Upon enactment, any person who destroyed, altered, or concealed any covered record after [date of introduction] shall be subject to..."; (c) add a provision that destruction after introduction creates an adverse inference in any proceeding under this Act; (d) explicitly cite 18 U.S.C. 1519 (Sarbanes-Oxley obstruction) as an existing legal basis for pre-enactment destruction.

**Affects:** Section 5.

---

## 11. Missing Definitions for Key Terms

**Problem:** Several critical terms are used but not defined in Section 1: "People Involved" (referenced in Schedule A/B but not in definitions), "investigation" (limited to criminal prosecution or includes any inquiry?), "death of Charlie Kirk" (date and location not specified as a legal matter), "Designated Trusted Investigator" (referenced in Section 6(a) but defined only in Law 4), "disclosure body" (referenced in Section 6(a) but never defined).

**Why it matters:** Undefined terms create ambiguity that agencies exploit. If "investigation" is not defined, DOJ could argue it only covers the state prosecution, not federal inquiries. If "disclosure body" is undefined, whistleblowers have no entity to send records to.

**Fix:** Add definitions for: (a) "investigation" -- broadly defined to include any federal, state, or local law enforcement or intelligence inquiry; (b) "death of Charlie Kirk" -- specify September 10, 2025, at Utah Valley University, Orem, Utah; (c) "disclosure body" -- define as the independent review board established under Section 8; (d) "People Involved" or "People Listed" -- incorporate by reference to Schedule B or define directly.

**Affects:** Section 1.

---

## 12. No Provision for Classified Records Handling Procedures

**Problem:** Section 4 eliminates most bases for withholding, but provides no mechanism for how classified records are to be declassified and released. No procedure for agency heads to request even temporary delays for declassification processing.

**Why it matters:** While the intent is to prevent agencies from hiding behind classification, some records will be classified under Executive Order 13526. Without a declassification procedure, agencies face conflicting legal obligations. This creates a legal limbo that agencies will exploit to delay indefinitely.

**Fix:** Add a provision stating: (a) all classification markings on covered records are automatically removed upon enactment; (b) no covered record may be reclassified; (c) agencies shall process declassification within the 30-day window; (d) classification does not excuse non-production -- records shall be produced to the review board in classified form if necessary, with a public redacted version produced simultaneously.

**Affects:** Section 4 or new subsection.

---

## 13. Budget Reduction Penalty is Constitutionally Questionable (Section 7(b))

**Problem:** Section 7(b) imposes automatic 25% budget reductions per month on non-compliant agencies. This is a self-executing appropriations cut, but Congress controls appropriations through the annual appropriations process, not through substantive legislation.

**Why it matters:** The Antideficiency Act and constitutional appropriations requirements may prevent automatic budget cuts without a separate appropriations action. Additionally, "25% per month" means after 4 months the agency's budget is effectively zero -- including the budget needed to comply with this law.

**Fix:** (a) Rewrite as a directive to the relevant appropriations subcommittees to reduce funding, rather than a self-executing cut; (b) alternatively, frame it as a withholding of new discretionary funds (prospective, not retroactive); (c) cap the reduction at 50% total to avoid destroying the agency's ability to comply; (d) exempt funds specifically appropriated for compliance with this Act from the reduction.

**Affects:** Section 7(b).

---

## 14. Disclaimer Appears Three Times -- Creates Legal Ambiguity

**Problem:** The identical disclaimer paragraph appears at three separate locations in the law text. Repeating a disclaimer that says "This document does not assert as fact that any individual... has committed any criminal, illegal, or immoral act" three times in a proposed federal statute is unusual and potentially undermines the law's authority.

**Why it matters:** A federal statute is a command, not a suggestion. The disclaimer language is appropriate for the GitHub repository and public advocacy documents, but in the actual statute text, it creates an argument that the underlying Schedule A items are speculative and that Congress itself does not believe the factual predicates. An opposing DOJ could argue: "Congress itself disclaimed that any wrongdoing occurred -- so why is this disclosure necessary?"

**Fix:** Remove the disclaimers from the statute body entirely. If a disclaimer is desired, place it once in a non-operative preamble or committee report, not in the operative text. The Congressional Findings section (Improvement #1) is where the factual basis should be established.

**Affects:** All three disclaimer locations in the law text.

---

## 15. No Conflict-of-Interest Provision for the Attorney General

**Problem:** The law requires the Attorney General to certify compliance (Section 10) and simultaneously makes the AG's non-compliance grounds for contempt (Section 7(d)). But if DOJ itself is implicated in the investigation (e.g., FBI cover-up allegations), the AG has a direct conflict of interest in controlling what gets disclosed.

**Why it matters:** The fox is guarding the henhouse. The AG can certify "compliance" while strategically withholding the most damaging materials. The independent review board can catch some of this, but the AG remains the primary compliance officer.

**Fix:** Add a provision that: (a) if the review board finds evidence that DOJ personnel are implicated in the investigation, compliance authority transfers to a court-appointed Special Master; (b) the AG must recuse from compliance decisions affecting records that could implicate DOJ personnel; (c) the review board, not the AG, has final authority to certify completeness.

**Affects:** Sections 7, 8, and 10.

---

## 16. No Provision for Handling Records from Private Entities

**Problem:** The law covers government agencies but many critical records are held by private entities: TPUSA, rental car companies, hotels, Mosaic Pro Events, AES, banks, telecom providers. Schedule A demands these records but the law only compels "covered agencies."

**Why it matters:** If the FBI has not subpoenaed records from TPUSA or rental car companies, those records do not exist within "covered agencies." The agency can truthfully say "we do not possess these records" without ever having sought them.

**Fix:** Add a provision requiring: (a) covered agencies to issue subpoenas for all records described in Schedule A within 15 days of enactment, regardless of whether they previously sought such records; (b) the review board to have independent subpoena power over private entities; (c) private entities that destroy records after notice shall be subject to the same penalties as government agencies.

**Affects:** Section 2 and Section 8.

---

## 17. No Anti-Retaliation Protection for Private Citizens and No NDA Override

**Problem:** Section 6 protects government employees from retaliation, and `Human_Requirements.md` calls for NDA/secrecy agreement override for both government employees AND private citizens. The current law does not override NDAs for private citizens or protect non-government witnesses from retaliation.

**Why it matters:** Many witnesses are TPUSA employees, contractors, hotel staff, and others bound by private NDAs. Without an NDA override, critical witnesses cannot come forward. This was specifically requested in Human_Requirements and has not been fully implemented.

**Fix:** Add a subsection to Section 6: (a) *"No non-disclosure agreement, confidentiality agreement, or similar contractual provision shall be enforceable to the extent it would prohibit any person from disclosing information related to the death of Charlie Kirk"*; (b) extend whistleblower protections to private sector employees who disclose information under this Act, modeled on 18 U.S.C. 1514A (Sarbanes-Oxley whistleblower provisions).

**Affects:** Section 6.

---

## 18. No Provision for Foreign Government Records or Diplomatic Channels

**Problem:** The investigation involves Egyptian aircraft, Israeli cell phones, and French connections, but the law only compels U.S. agencies. There is no mechanism for requesting records from foreign governments through diplomatic channels, mutual legal assistance treaties (MLATs), or Interpol.

**Why it matters:** Some of the most critical evidence (who was on the Egyptian planes, what the Israeli phones were doing) may reside with foreign governments. Without a directive to pursue these records through diplomatic channels, the law has a jurisdictional gap.

**Fix:** Add a provision requiring: (a) the Secretary of State to invoke applicable MLATs with Egypt, Israel, and France within 15 days; (b) the AG to submit formal requests through Interpol channels; (c) disclosure of any prior diplomatic communications regarding the investigation; (d) if foreign governments refuse cooperation, that refusal must be publicly reported.

**Affects:** New section or addition to Section 2.

---

## 19. Schedule A Items Use Advocacy Language Rather Than Legislative Language

**Problem:** Many Schedule A items contain phrases like "Also include all information on..." and use narrative, discovery-style language rather than formal statutory directive language. For example: "Include all information the FBI has on the following aircraft" reads like a discovery request, not a statute.

**Why it matters:** Legislative drafters and courts expect mandatory statutory language ("The covered agency shall produce..."). Discovery-style language could be interpreted as precatory (requesting rather than commanding). It suggests the Schedule A was not drafted with legislative intent, weakening its force.

**Fix:** Rewrite each Schedule A item to use mandatory statutory language: "Each covered agency shall produce [specific records]." This is a significant rewrite but important for enforceability.

**Affects:** All of Schedule A (200+ items).

---

## 20. Missing Effective Date for Criminal Penalties -- Ex Post Facto Issue

**Problem:** Section 7(a) criminalizes "willfully withholding" records but does not specify when this duty begins. Section 5(b) criminalizes destruction "after the date this bill is introduced" -- before enactment.

**Why it matters:** The Ex Post Facto Clause (Article I, Section 9) prohibits criminalizing conduct that was lawful when performed. The duty to disclose only arises upon enactment. Criminal liability cannot apply retroactively to the date of introduction.

**Fix:** (a) Clarify that criminal liability under Section 7(a) applies only to withholding that continues after enactment; (b) fix Section 5(b) as described in Improvement #10; (c) add a general provision that all criminal penalties apply prospectively from the date of enactment.

**Affects:** Sections 5(b), 7(a), 13.

---

## 21. No Provision for Interim/Rolling Disclosure

**Problem:** The law requires full disclosure within 30 days but provides no mechanism for rolling or interim disclosures. Agencies may wait until day 30, dump millions of pages, and claim compliance.

**Why it matters:** Document dumps are a known evasion tactic. The Epstein Act suffered from this -- DOJ waited near the deadline and released an incomplete batch. Without interim milestones, there is no way to gauge compliance until the deadline passes.

**Fix:** Add interim milestones: (a) within 7 days, produce an index of all identified covered records with estimated page counts; (b) within 14 days, produce all records already in digital format; (c) within 21 days, produce all remaining records; (d) within 30 days, certify completeness. The review board monitors each milestone.

**Affects:** Section 2.

---

## 22. Treasury Department and IRS Not Explicitly Listed as Covered Agencies

**Problem:** `Human_Requirements.md` specifically calls for Treasury and IRS to be covered, but Section 1(a) lists ATF, CBP, TSA, DHS, and FinCEN without explicitly naming the Department of the Treasury or the Internal Revenue Service.

**Why it matters:** FinCEN is a bureau of Treasury, but Treasury itself has broader records. The IRS has tax records and financial investigation files that could be relevant (e.g., TPUSA's tax-exempt status, financial flows). This was a specific requirement from Human_Requirements that was not implemented.

**Fix:** Add "the Department of the Treasury, the Internal Revenue Service" to the list in Section 1(a).

**Affects:** Section 1(a).

---

## 23. No Short Title

**Problem:** The law uses "The Charlie Kirk Files Forced Disclosure Act - Law Enforcement" as a heading but does not include a formal short title provision.

**Why it matters:** All federal statutes include a short title section for citation purposes. Without it, there is no standard way to reference the law in court filings, Federal Register notices, or subsequent legislation.

**Fix:** Add Section 1 (renumbering current sections): *"This Act may be cited as the 'Charlie Kirk Files Forced Disclosure Act.'"*

**Affects:** Beginning of the law (before current Section 1).

---

## 24. No Statute of Limitations for Criminal Penalties

**Problem:** The law creates multiple criminal offenses (withholding: 10 years; destruction: 15 years; retaliation: 5 years) but does not specify a statute of limitations for prosecution.

**Why it matters:** Without a specified limitations period, the default 5-year federal statute of limitations (18 U.S.C. 3282) applies, which may be too short for destruction of records discovered years later. The 10- and 15-year sentence maximums suggest Congress intended these as serious offenses warranting a longer limitations period.

**Fix:** Add a provision: *"No prosecution under this Act shall be barred by the passage of time. The statute of limitations for any offense under this Act shall be 15 years from the date the offense is discovered."*

**Affects:** Section 7 or new section.

---

## 25. Schedule B (People Listed) is Referenced but Not Attached

**Problem:** Schedule A references "People Listed" as defined in "Schedule B" with 35 categories (P1 through P35), and the summary appears in the Schedule A preamble. But Schedule B itself (the detailed 35-category definition from `other/people.md`) is not actually attached to or incorporated in the law.

**Why it matters:** If Schedule B is not part of the enacted statute, agencies can argue the "People Listed" categories are non-binding.

**Fix:** Either: (a) incorporate Schedule B by reference with a specific URL and date; (b) append Schedule B directly to the law; or (c) incorporate the 35 categories into Section 1 as a definition.

**Affects:** Section 1 and Schedule A preamble.

---

## 26. No Provision Addressing the Pending Criminal Prosecution of Tyler Robinson

**Problem:** The law mandates disclosure of all investigation records while a criminal prosecution is pending in *State of Utah v. Tyler Alexander Robinson*. Section 4(a)(2) says records cannot be withheld based on "any ongoing investigation" except as "narrowly provided below" -- but there is no narrow provision addressing the active prosecution.

**Why it matters:** Utah prosecutors will argue that mass disclosure could prejudice the prosecution, taint the jury pool, or violate Robinson's Sixth Amendment fair trial rights. A court could enjoin the law on due process grounds.

**Fix:** Add a provision: (a) acknowledging the pending prosecution; (b) stating that disclosure does not constitute a determination of any fact in the criminal case; (c) if the trial court determines specific records would irreparably prejudice the defendant's fair trial right, those records may be produced under seal to the review board and defense counsel, with public release deferred until after trial; (d) this exception expires upon conclusion of the criminal case.

**Affects:** Section 4.

---

## 27. "Searchable and Downloadable Format" Needs Technical Specification (Section 2(a))

**Problem:** Section 2(a) requires records be "publicly available in a searchable and downloadable format" but does not specify technical requirements.

**Why it matters:** Agencies have complied with similar mandates by producing scanned images of documents (technically "downloadable" but not text-searchable), or by posting to obscure government websites.

**Fix:** Specify: (a) text-searchable PDF or original digital format; (b) OCR required for scanned documents; (c) hosted on a publicly accessible website with no login required; (d) bulk download capability; (e) a machine-readable index of all documents.

**Affects:** Section 2(a).

---

## 28. Cross-Reference to Laws 2-4 is Missing

**Problem:** The law does not reference or coordinate with the companion laws (Law 2: Intelligence; Law 3: Investigation; Law 4: Trusted Investigators), despite the project instructions stating each law should cross-reference the others.

**Why it matters:** Without cross-references, there could be gaps or conflicts. Section 6(a) references "Designated Trusted Investigators" from Law 4, but if Law 4 is not enacted, that reference is meaningless.

**Fix:** Add a section on "Relationship to Other Acts": (a) reference the companion intelligence disclosure act; (b) state that this Act applies independently and does not depend on enactment of companion legislation; (c) define "Designated Trusted Investigator" locally, or make the reference conditional on Law 4's enactment.

**Affects:** Section 6(a), new coordination section.

---

## 29. No Agency Bad Faith or Adverse Inference Provision

**Problem:** If an agency claims records were "lost" or "destroyed," Section 4(a)(6) says this cannot be used as a basis for withholding "without forensic verification," but there is no evidentiary consequence for the destruction itself beyond criminal penalties (which require proof of willfulness).

**Why it matters:** An agency could claim records were "inadvertently" destroyed and face no evidentiary consequence. In litigation, destroyed evidence triggers adverse inference instructions, but this law does not create such a presumption.

**Fix:** Add: *"In any judicial, congressional, or administrative proceeding, the destruction or loss of covered records by a covered agency shall create a rebuttable presumption that the destroyed records contained information adverse to the agency's position and favorable to full disclosure."*

**Affects:** Section 4 or Section 5.

---

## 30. Contempt of Congress Provision is Toothless (Section 7(d))

**Problem:** Section 7(d) says AG non-compliance is "grounds for contempt of Congress proceedings" but does not specify the mechanism (inherent contempt, statutory contempt under 2 U.S.C. 192, or civil contempt through the courts).

**Why it matters:** Congressional contempt has historically been nearly unenforceable. Statutory contempt requires referral to the U.S. Attorney for the District of Columbia -- who works for the very AG being held in contempt. Inherent contempt (the Sergeant-at-Arms power) has not been used since 1935.

**Fix:** Specify: (a) Congress may proceed through civil contempt in federal court (bypassing the DOJ referral problem); (b) authorize either chamber to retain independent counsel to prosecute the contempt; (c) authorize the review board to seek judicial enforcement directly.

**Affects:** Section 7(d).
