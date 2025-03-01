**Using Multiple Engineered Cells for Coordinated Attack**

Jeremy Stubbs MD<sup>1</sup>

<sup>1</sup>Independent Researcher, United States of America

<jeremyb.stubbs@gmail.com>

**Keywords**

Immunotherapy, Antibody, Granulocytes, Eosinophils, Neutrophils, NK cells, T-cells, Crispr

**Abstract**

Metastatic cancer remains a significant clinical challenge with limited therapeutic options. This papers reviews cancer immunotherapy and proposes a novel approach which involves engineering multiple immune cell types to achieve synergistic anti-cancer effects. Where my proposal differs from others is I introduce a paradigm where granulocytes are used to get access to the tumor and then T cells and NK cells finish the job. I further propose specific molecular targets to achieve this goal. There are two options for signal transduction: Chimeric Antigen Receptors (CAR) and Chimeric Fcγ Receptors (CFcγR). Each has its advantages and disadvantages. CFcγRs are scalable and cost-effective, and do not require computational models to attain tumor specificity because that can be determined empirically by antibody screening assays. Alternatively, AI and advanced DNA chemistry provide the ability to find targets and create oligonucleotides for creation of chimeric receptors. To make a truly scalable approach, universal donor cells are needed. I believe this will be easier to create with granulocytes (I specifically discuss neutrophils). Alternatively, we could differentiate patient-derived iPSCs into granulocytes ex vivo. Granulocyte genomes are notoriously difficult to edit, but progress has been made.

**Introduction**

It is clear that immune cells can fight cancer, but it is difficult to find effective tumor-associate antigen (TAA) targets for solid tumors. There are over 50 FDA approved monoclonal TAA antibody therapies for cancer and not one provides excellent improvement in overall survival. \[5, 8, 9, 18\] Some commonly used antibodies that target overexpressed surface antigens are Cetuximab and Trastuzumab. Bispecific T-cell Engager (BITEs) are a promising prospect under development and already first line for some blood cancers e.g. blinatumomab. \[34, 35\] But the standard of care (SOC) for many metastatic solid tumors is immune stimulating antibodies that target the PD-1 ligand and CTLA-4.

There are multiple other options to stimulate the immune system to target cancer cells: mRNA vaccines, autologous inactivated vaccines, intratumoral therapies (virus-based and immunostimulant-based). There is evidence that adding these therapies enhances the effect of PDL and CTLA-4 antibodies (T-VEC, SD-101, RP1, mrna-4157) in multiple ongoing clinical trials. \[39\] Another option is antibody-drug complexes (ADCs).

CAR T cells have found success in blood cancers. The 5-year overall survival of CD-19 targeting CAR T cell therapy for lymphoma/leukemia is 40-60%. \[28, 29, 33\] Why haven’t they been effective in solid tumors like immunostimulant-based approaches? Tumor penetration difficulties and off-target effects. The root cause limitations of TAA antibodies overlaps with that of CAR cells

But we must consider the possibility that combinations of the above therapies will have only a modest effect. Furthermore, we must consider that another revolutionary small molecule target like PDL and CTLA4 may not be found. Other approaches are needed.

I think that PDL and CTLA-4 antibodies work better than CAR cells in solid tumors because they either activate or expand existing tumor-infiltrating lymphocytes (TILs) or recruit a wide range of cells (T cells, NK cells, B cells, and granulocytes) that can better coordinate a response in the complex tumor environment. There is little to no evidence that any vaccination technology or any other small molecules can activate or expand TILs. Furthermore, there has been limited success in turning cultured T cells into TILs. In the case of better immune cell coordination, I think engineered cells could do it better than endogenous cells (which are currently used by immune activating approaches) because they could be programmed for better tumor penetration and survival. Frankly, the culture environment and genetic changes needed to make TILs from T cells are about as complicated as my proposal. Both should be explored.

What cells to use? T and NK cells offer extremely effective targeted cytotoxicity. They clearly have a role. Highly engineered granulocytes offer the possibility of a messy attack which would help overcome tumor heterogeneity. Whereas T cells are like snipers, a granulocyte is like a bomb that would hit the target cell and everything around it, thus opening the door for the T cells and NK cells. To utilize granulocytes like this requires a paradigm shift in thinking. Instead of trying to accentuate their natural behavior you would reprogram them heavily.

There are two options for signal transduction: Chimeric Fcγ Receptors (CFcγR) and Chimeric Antigen Receptors (CAR). Without universal donor cells, these must be engineered for each patient from iPSCs, and the only difference is whether the TAA is determined empirically (CFcγR) or calculated (CAR). TAAs are often similar between patients so with a universal donor cell, CARs could be slightly interchangeable between patients. Whereas with CFcγRs, the TAAs would be determined from antibody screening assays, and the cells would be fully interchangeable. In either case, you would link the CAR or CFcγR motif to multiple signal transduction pathways on the same cell and use multiple cell lines.

Chimeric Fcγ receptors were initially created in T cells by linking the external Fc-binding motif linked to CD3. The benefit of using chimeric Fcγ receptors over CAR-based therapies is only evident if you have a universal donor cell because all the cells and all their receptors would respond to the same antibodies. You just screen a surgical tumor sample to identify antibodies that bind to it than build unique cell for each patient. This seems easier and possibly more accurate than sequencing multiple parts of a tumor and using AI to determine targets. But chimeric antigen receptors (CAR) are also a possibility.

Eshhar and colleagues first developed chimeric Fc gamma receptor T cells in 1989 to study the activating pathways of T cells \[38\]. He later focused on the development of CAR T cells. Others have followed in his footsteps. \[25, 37\] I make no limitation on the signal transduction domain. It could be an Fc receptor or it could be something entirely different like those explored in BITE technology. The key is to engineer cells that respond optimally when the target binds the linker molecule (BITE or antibody).

There has been incredible progress in developing universal cells for transplantation and immunotherapy. Advancements in biotechnology have made this nearly a reality. The problems with granulocytes are they are terminal cells that are difficult to culture, they have to be vastly reprogrammed because their role in cancer is complicated, and there is very little experience in successful genetic engineering of them. Progress has been made on all of those issues. Sugimura, Takata and others have developed neutrophils from iPSCs. \[3, 17\] Furthermore, systems have been developed to efficiently use CRISPR on B cells and granulocytes. \[10, 15-17\]

**Neutrophils vs T Cells**

**Neutrophils (Easier to Universalize)**

Neutrophils are part of the innate immune system and have a more transient presence in circulation, meaning they are less prone to long-term graft-versus-host disease (GVHD) and immune rejection. Key targets for engineering universal donor neutrophils:

1. **HLA Class I (HLA-A, HLA-B, HLA-C) Knockout**
    - HLA-I is the primary target for host cytotoxic T cells and NK cell-mediated rejection. Neutrophils weakly express this and knocking it out would likely not result in rejection.
    - **Solution:** Knockout HLA-I completely and introduce HLA-E or HLA-G to inhibit NK cell activation.
2. **CD47 Overexpression ("Don't Eat Me" Signal)**
    - Macrophages and dendritic cells use CD47-SIRPα interactions to avoid engulfing host cells.
    - **Solution:** Overexpress CD47 to evade phagocytosis.
3. **Beta-2 Microglobulin (B2M) Knockout**
    - B2M is required for proper HLA-I expression and stability. Removing it disrupts antigen presentation.
    - **Solution:** Knock out B2M, but co-express non-polymorphic HLA-E/G to avoid NK rejection.
4. **Fc Receptor Modifications (FcγRII/III Engineering)**
    - Neutrophils rely on Fc receptors (FcγRs) for ADCC and phagocytosis, which vary between individuals.
    - **Solution:** Engineer a universal FcγR profile to ensure compatibility with therapeutic antibodies.
5. **Short Lifespan Reduces Rejection Risk**
    - Unlike T cells, neutrophils have a lifespan of ~1–2 days. This makes them a transient therapy, reducing the need for long-term immune evasion strategies.

**T Cells (Harder to Universalize)**

T cells are much more challenging to engineer for universal use due to their role in adaptive immunity and potential for GVHD. Key molecular targets:

1. **TCR Knockout (TRAC/TRBC Deletion)**
    - Native T cell receptors (TCRs) can recognize host antigens and trigger GVHD.
    - **Solution:** Knock out TRAC (TCR alpha constant) and TRBC (TCR beta constant) genes to remove native TCRs.
2. **HLA Class I and II Knockout (HLA-A, HLA-B, HLA-C, HLA-DR, HLA-DP, HLA-DQ)**
    - Adaptive immune cells like T cells are highly sensitive to HLA mismatch.
    - **Solution:** Knockout HLA-I/II and replace with HLA-E/G for NK evasion.
3. **CD47 Overexpression**
    - Similar to neutrophils, engineered T cells can overexpress CD47 to evade macrophages.
4. **CISH Knockout to Improve Persistence**
    - **CISH** is a negative regulator of cytokine signaling. Knocking it out improves T cell survival.
5. **Cytokine-Independence (IL-7R/IL-15R Engineering)**
    - T cells rely on IL-7 and IL-15 for survival.
    - **Solution:** Engineer cells with constitutively active IL-7R/IL-15R signaling to improve persistence.

**Final Verdict: Neutrophils Are Easier to Engineer**

- **Fewer rejection concerns:** Neutrophils lack antigen-specific receptors (TCR/BCR), reducing GVHD risk.
- **Shorter lifespan reduces immune clearance pressure:** They don't need extensive immune evasion strategies like long-lived T cells.
- **Simpler immune escape mechanisms:** HLA-I knockout with HLA-E/G expression is likely sufficient, whereas T cells require multiple knockouts and immune checkpoint engineering.

If you're designing a universal immune cell therapy, neutrophils could be a more practical starting point, especially for applications like antibody-dependent cell-mediated cytotoxicity (ADCC) or acute infection control.

Plus, I don’t think anyone has considered the practical possibility that you can treat a patient with steroids and other drugs to prevent rejection of imperfectly matched transplants. The combination of new biotechnology directed at making universal cells and active immunosuppression may create an entirely new avenue of cancer treatment. Keep in mind you only need the cells to live for a short period of time to perform their function, so you don’t need to keep the patient immunosuppressed.

**The Strategy:**

Create multiple cell lines from iPSCs that signal through multiple activating pathways. These would be either universal donor cells or derived from the patient.

For CFcγRs, all the signal transduction pathways on all the cells would use the same surface antigen(s) on the tumor via the common antibody or BITE. I imagine a future in which there are thousands of anti-cancer antibodies, and you can screen a tumor sample to see which ones bind the patient’s particular cancer phenotype. Since the cells recognize the same Fc portion, the same cells could be used for all patients.

For CARs, each pathway on each cell line would be created separately. Functionally this is the same as the CFcγR approach except they do not require a linker molecule.

This strategy could be used with T cells, NK cells, macrophages, neutrophils, B cells and granulocytes. Great advances have been made in producing both universal cells and growing immune cells from pluripotent stem cells which can be grown and cultured ex vivo.

Taking it a step further (possibly into dreamland), you could engineer cells to respond not just to antibodies but also the molecules carried by ADCs.

For CFcγRs, the Fc region of IgG is remarkably consistent between people, but you must ensure that these cells are not activated by all the other antibodies in the blood. You will need to use an IgG with a modified Fc peptide sequence and mutate the engineered cells FcγR’s external domain to respond only to this modified sequence. Most immune cells require multiple signals to become activated. \[3\] The solid tumor environment is highly immune-inhibitory and difficult to access. \[3\] Significant engineering needs to be done for each cell line.

What about losing the endogenous immune response from the steroid treatment? A possible solution is to alternate: one week or month you give modified antibodies and the engineered cells that respond to them; the next you give normal IgG antibodies or other approaches that use endogenous immune system.

**Specific Targets**

In general, you should target the cell’s main activating signals and other stimulatory pathways. You must also make the cells tolerant to the tumor environment and not get attacked by the patient’s immune system.

1) For CD8 T cells, you could conjugate the external Fc receptor to CD3. You could also link it to the co-receptors that bind helper T cells. For B cells, you might target the B cell receptor and its co-receptors. For granulocytes you could target innate immune pathways. For example, you might link the Fc binding domain to a TLR receptor (like TLR4 for lipopolysaccharide). For NK cells, consider CD16, NKG2D, NKp30. Antibodies alone are a strong activation signal for immune cells. You might retain some native Fc receptors in these cells.  

2) The cells could also be modified to tolerate the tumor microenvironment’s suppressive signals. I would try to knock out a gene for one or more of the known immunosuppressive signaling molecules. Try knocking out receptors for the PD-1 ligand and CTLA-4. Try upregulating CD47. There are a variety of other potential targets that could include receptors for IL-1β, TGF-β/NF-κB and IL-6. Hypoxia-inducible factor pathway might also be altered. Heat-shock proteins (HSP) are often secreted by cancer cells and inhibit immune cells. \[3, 4, 8\] There are many options.  

3) Taking it a step further, cytokines and chemokines often signal through JAK-STAT pathways. JAK phosphorylation catalyzes downstream dimerization and signaling. You might connect these to the Fc receptor by cross-linking it to PI3K (the Fc signal transducer) or STAT (the cytokine signal transducer).

4) You might also increase the effectiveness of the cells by making them produce certain molecules in response to the antibodies/BITEs: 1. Chemokines 2. Cytokines 3. Exotoxins. Chemokines would attract other immune cells. Cytokines would augment the endogenous immune response to antibodies in the vicinity of the tumor. Common CD8 T cell cytokines are TNF, TGF-B, IL-12, IL-6, and IL-2. Engleman showed that neutrophils infiltrate and eliminate cancer when TNF + CD40 agonist + anti-tumor antibodies injected into tumors. \[24\] For neutrophils and eosinophils, I would focus on C3a, C5, IL-5, GMCSF, IFN and TNF.

5) Lastly, you want these cells to live long enough in the patient’s body to do their work. There are many surface protein/glycoprotein markers that determine long-term compatibility of exogenous cells. The main histocompatibility markers are HLA-1 and HLA-2. Less significant ones includes various integrins and the ABO blood groups. HLA 1 knockout cells have been created which are widely compatible much like the O blood type. \[26\] There are far fewer combinations of HLA 2 which would make creating or finding a matched cell line much easier. The key is not to lose function. With a steroid pretreatment, you could probably make universal cells.

This could all be accomplished with CRISPR or zinc-fingers and other standard genetic engineering strategies. Growing and editing T cells for CAR T cell therapies is commonplace. Sugimura and Takata have developed neutrophils from iPSCs. \[3, 17\] Furthermore, systems have been developed to efficiently use CRISPR on B cells and granulocytes. \[10, 15-17\]

In summary, in response to IgG the cells would activate multiple pathways on multiple heavily engineered cells. These would coordinate an attack on the tumor to which the antibodies are bound.

**The Argument for Granulocytes:**

It is a given that T cells, NK cells and B cells probably have a role. Although granulocyte are not canonically anti-cancer cells, I think they have great potential in this regard. It will be easier to make a universal granulocyte than a universal T cell and they do not require MHC matching to identify target. This makes engineering of antigen receptors easier as you wouldn't have to make sure it works with a certain TCR.

Granulocytes are the major white blood cell fraction. The three varieties of granulocytes are neutrophils, eosinophils and basophils. Morphologically, the cells are similar, ranging in size from 12 to 17 µm with multi-lobed nuclei. Their cytoplasms contain granules whose eponymous staining pattern differentiates them. Degranulation only occurs under the right conditions and is part of the mechanism by which they accomplish their functions. \[3, 4, 8, 11, 12\] Neutrophils are the most numerous. They are associated with phagocytosis and various cytotoxic and immunostimulatory actions in purulent infections. Eosinophils are best known for their activities against helminth infections and in allergic reactions. Basophils and mast cells are best known for their roles in allergic reactions. \[3\] But there is a great deal of overlap in the immune system and these cells are multifunctional. Degranulation is the process in which the contents of vast numbers of granules are released simultaneously. Eosinophils use it to attack a large multicellular helminth infection. \[21\] Neutrophils are classically activated against bacterial infections. But there is a great deal of overlap in the immune system and many groups are trying to harness these to attack cancer cells.

Degranulation offers a unique ability of a messy attack. Whereas T cells are targeted killers, a granulocyte is like a bomb that would hit the target cell and everything around it. This confers the possibly of breaking through the extracellular matrix which usually prevents the access of immune cells to tumors. This might work better in conjunction with other immune cells. One way to visualize it is, the granulocytes would knock down the door (C4) and let the T-cells enter to perform a targeted attack (Navy seals).

Eosinophils should get the same amount of funding as neutrophils because there is reason to believe that they are just as promising. \[23\] Eosinophils live longer (up to seven days versus 24 hours in neutrophils) and their granules are less heterogeneous than those of neutrophils. MBP comprises 50% of their granule content which represents a single alterable target that could be replaced with a more cytotoxic protein. \[3, 4\] For example, the genes for granule proteins could be replaced with another more toxic protein like perforin, granzyme and/or pseudomonas exotoxin. CRISPR could be used to edit the genes. Granularity allows for production of an exotoxin because it would be safely segregated from the rest of the cell.

**Discussion**

CAR T cells are limited by poor penetration and off target effects. The biotech community argues that mRNA vaccines may recruit TILs and/or provide a broader immune response than CAR cells. It is possible that mRNA vaccines will result in a better immune response and give better results, but I think engineered cells could be even better. The ultimate plan is to use vaccines, CAR T and NK cells, and immunomodulatory drugs to overcome these problems. I hope that the combination of cancer vaccines, immunotherapies and CAR T/NK cells show some benefit for metastatic cancer. But we should consider my proposal too while trying to develop TIL technology.

Universal neutrophils and eosinophils will be easier to make than universal T cells and offer unique possibilities. But they require a paradigm shift in thinking. Instead of trying to accentuate their natural behavior, you would reprogram them entirely. Without universal cells, you would have to culture and differentiate these cells from iPSCs. The difference between choosing CAR or CFcγR in my approach depends on the ability to achieve universal donor cells. If possible, CFcγRs greatly simply the process of finding a TAA. Using iPSCs, the difference is less pronounced – the question becomes do you find the TAA empirically with antibody binding assay or calculate it from genome sequencing with AI? Targeted panels will help CARs. An advantage of CFcγRs is there are already over 50 FDA approved monoclonal antibody therapies for cancer. \[5, 8, 9, 18\] We might increase their effectiveness with the right combination of engineered cells. Each target must be tested to ensure that they do not target any “normal” proteins in the body. But I think cancer patients would be willing to take a little risk to treat their cancer, and I think they should be allowed to try experimental therapies. This proposal clearly does not work with cancer cells that do not have a TAA.

I propose specific targets for the antigen-targeting receptors for each T cells, NK cells, B cells, neutrophils, and eosinophils. The cells would be engineered to tolerate the tumor environment. Hypothetically, you could also make these cells respond to antibody-drug complexes in addition to regular antibodies. This strategy could also be used in combinations with non-cellular immunotherapies.

The biotech community argues that eosinophils and neutrophils are 1. Too complex to engineer 2. There’s a lack of knowledge of their role in cancer, 3. Have too short lifespan. I think that all of these are either non-issues/not a good reason or surmountable. Progress has been made to answer all of those issues. There is a clear benefit of neutrophils and eosinophils over T cells: 1. They do not require MHC matching to identify target which could potentially make antigen targeting easier as you wouldn't have to make sure it works with a certain TCR. 2. It will be easier to make a universal granulocyte than a universal T cell or NK cell.

This is a massive proposal. This would require significant funding and the concerted effort of many scientists and engineers, but I think it is worth it. Plus, it could be combined with many other approaches.

**Nomenclature**

NK cells: natural killer cells

MBP: major basic protein

CRISPR: clustered regularly interspaced short palindromic repeats

IgG, IgA, SigA: immunoglobulins

FcαR, FcγR: immunoglobulin receptors

TLR: toll-like receptor

EGFR: epidermal growth factor receptor

iPSCs: induced pluripotent stem cells

ISAC: immune stimulating antibody conjugates

C3a, C5, IL-5, GMCSF, IFN, TNF, IL-1β, TGF-β/NF-κB and IL-6: cytokines/specific signaling molecules

**Conflict of Interest**

The authors declare that the research was conducted in the absence of any commercial or financial relationships that could be construed as a potential conflict of interest.

**Author Contributions**

I, Jeremy Stubbs, conceived and authored the entire manuscript.

**Funding**

This is manuscript has received no funding.

**Acknowledgments**

I would like to thank my family.

**References**

1) Celularity. (2022). [](%20)[https://celularity.com/](https://l.facebook.com/l.php?u=https%3A%2F%2Fcelularity.com%2F%3Ffbclid%3DIwAR0tl3IYgXGube32UIlFLVVCNChTuIzXHAwk3eXusIr2syB1U3x7pSO6Pk0&h=AT0E_V7fCcHKjECOzNLlxAc8cao38sZ3OWb0u7i3H3gXqLFG-01edSIhZ5xYd5JwZcb2c49N9i2oBz9dU4miLXqSrQKgzbwG9iD8X__uf5TBNYEY1U0u51W0kZxIQEZQVFD1kVX7T_ot0QC6uXERBrE&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA). \[Accessed 12/15/2023\]

2) Mersana. (2022). [https://www.mersana.com/](https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.mersana.com%2F%3Ffbclid%3DIwAR1WjpxWTRet7Dxnbbx14-xj-c4YP5nrKqg190PXOCrLFj_A3UBvyauI29Y&h=AT1Y3_lVYLqJ_DkpUXaBQzhNfnnlvBh2PHVFStGRUks8-48Xm5udPjH6iqbIR-xkH6ILpKoFRCAwzb6GRhdRy1jJTRxJkxZJ8qN06gsPkbWDGb5VOPdhS91tslpe-0KYU3S7d31IvqE9YiyuR0l5IR4&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA). \[Accessed 12/15/2023\]

3) Firestein, Gary S, and William N Kelley. Kelley's Textbook Of Rheumatology. Saunders/Elsevier, 2012.

4) McBrien, Claire N., and Andrew Menzies-Gow. "The Biology Of Eosinophils And Their Role In Asthma". Frontiers In Medicine, vol 4, 2017. Frontiers Media SA, [https://doi.org/10.3389/fmed.2017.00093](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.3389%2Ffmed.2017.00093%3Ffbclid%3DIwAR1YR3BW2blouoSURqSxQmQkHNR28OAKzplJJrvD4O8Pv5FI2GqylVyF72s&h=AT0lwvKIt2fEQjLBBeW7NPaGcIrtsQ3OZqzB7FrqNHz5lul8hlnRhksptjF3K9qZNxYajUmXCuxrDIn26nW7R7lGdf9mFWbNgSuWJbNubtFsM158XDM4k6OzuRIkiWBui7sZ8HGt8jO3sf7Z94OTEW4&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

5) Grisaru-Tal, Sharon et al. "A New Dawn For Eosinophils In The Tumour Microenvironment". Nature Reviews Cancer, vol 20, no. 10, 2020, pp. 594-607. Springer Science And Business Media LLC, [https://doi.org/10.1038/s41568-020-0283-9](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1038%2Fs41568-020-0283-9%3Ffbclid%3DIwAR0lMZFUSHwX_2q45oAjKbU2dGezcUhrgtRQtug2lGITIoNzqurHoYASWA4&h=AT21uYrd0piMZ1j7bBiaVW--bP-aL_E-VecpRGMmh4C9evqLba6NK11oajuVrS80Zg0O3Me7NZvbIYtm4fSqon3q8eBu5gLxXdHUTT28ATR3rLKGNe7GXKUZCnMabYKA7TglQXlI-6ZrU4FzTDmo6RU&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

6) Hedrick, Catherine C., and Ilaria Malanchi. "Neutrophils In Cancer: Heterogeneous And Multifaceted". Nature Reviews Immunology, vol 22, no. 3, 2021, pp. 173-187. Springer Science And Business Media LLC, [https://doi.org/10.1038/s41577-021-00571-6](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1038%2Fs41577-021-00571-6%3Ffbclid%3DIwAR3j9xSSR_p3T72ohjWa8LVLaJ40AybUgVoUWu1V66dW8gQC--nSA1MrW_4&h=AT0QpS55HczlDKNkppmiuMkNMJrJR6YtDuezG4pXYzMMv4S-Y6orGsrXWEUYeVA8_JqHDZpCM13joAsAeuB205UxNGM1332R0ZG24yUeqzTBA8QuLxGl6vN0DPT9bS0iZ_TteHI6C8182-fjztTrQrg&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

7) Lu, Thomas, and Marc Rothenberg. "Bone Marrow Derived Eosinophil Cultures". BIO-PROTOCOL, vol 4, no. 12, 2014. Bio-Protocol, LLC, [https://doi.org/10.21769/bioprotoc.1161](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.21769%2Fbioprotoc.1161%3Ffbclid%3DIwAR2IWT2OsncJEzzEGZMl1za4s2yEc8jLCdoE5nGiuyOQv-E7hJch1t8eDKw&h=AT2jNfwmv9EsymouyBzpV9TzeOfSwIbGXekE00W9pe6lC81ArPQUYOufcx5jUaDLflj5MFIBo4thQ0xjz6TtPgwsUzxtO9roJzfHd5RHC7KUHz5fto-DhSXKAqmg1gXJrLIGLbkknXO2SZZ6SujiP1o&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

8) Varricchi, Gilda et al. “Eosinophils: The unsung heroes in cancer?.” Oncoimmunology vol. 7,2 e1393134. 13 Nov. 2017, doi:10.1080/2162402X.2017.1393134

9) Baldo, B.A. Monoclonal Antibodies Approved for Cancer Therapy. In Safety of Biologics Therapy: Monoclonal Antibodies, Cytokines, Fusion Proteins, Hormones, Enzymes, Coagulation Proteins, Vaccines, Botulinum Toxins; Baldo, B.A., Ed.; Springer International Publishing: Cham, Switzerland, 2016; pp. 57–140. ISBN 978-3-319-30472-4.

10) Khoury, Paneez et al. "Revisiting The NIH Taskforce On The Research Needs Of Eosinophil-Associated Diseases (RE-TREAD)". Journal Of Leukocyte Biology, vol 104, no. 1, 2018, pp. 69-83. Wiley, [https://doi.org/10.1002/jlb.5mr0118-028r](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1002%2Fjlb.5mr0118-028r%3Ffbclid%3DIwAR1FxBwm7h29Zl3-H6bHcsjPbR4dbWV7YODVqT84ZSr6H2tA3T-qJ9ps11g&h=AT2vnbR5XzevZvcs9qR0Ef91mX6_Ti7FkYEPN7QMv67T-ekKE9F5T-hrL4TlnE57thYjGV_aQYMtfEi7PJXGlAYvHyZZDJLGskt-FwEzaWb4kF5EYp3mC-DHk9TOzBKLuv0oUROPerRF5U0tMgB8Xvk&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

11) Lacy, Paige. "Mechanisms Of Degranulation In Neutrophils". Allergy, Asthma &Amp; Clinical Immunology, vol 2, no. 3, 2006. Springer Science And Business Media LLC, [https://doi.org/10.1186/1710-1492-2-3-98](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1186%2F1710-1492-2-3-98%3Ffbclid%3DIwAR0tl3IYgXGube32UIlFLVVCNChTuIzXHAwk3eXusIr2syB1U3x7pSO6Pk0&h=AT1zTazaMJLg9vKJB-qsr49bShdpZRPefV6XHgih-yTj1n8MNfNuxHsr-hyyqLwsqDpITQs2NjxXqra2_kSsPdWtakT09iMaaYE_eQmZn6iw3_ybDU887_8IyHYr09YDh2q4GMt95zYFCRfqP1oaUv0&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

12) Rothenberg, Marc and Kunnathur, Vidhya. Sleisenger and Fordtran's Gastrointestinal and Liver Disease, chapter "Eosinophilic Disorders of the Gastrointestinal Tract" , 424-434.e5. Elsevier, 2020.  

13) Chang, J. et al. "Reconstitution of haemopoietic system with autologous marrow taken during relapse of acute myeloblastic leukaemia and grown in long-term culture". The Lancet, vol 327, no. 8476, 1986, pp. 294-295. Elsevier BV, [https://doi.org/10.1016/s0140-6736(86)90828-7](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1016%2Fs0140-6736%2886%2990828-7%3Ffbclid%3DIwAR1WjpxWTRet7Dxnbbx14-xj-c4YP5nrKqg190PXOCrLFj_A3UBvyauI29Y&h=AT1ocV9AkDw1uCrkKCoX2h_cV_QPYPOuLAJh5JCKYyogIhUQ1nfMQeag7TnFRMuUrxlKawVWAo6CXcIuyhcUzhBQzL31WHknbiE1odUVz4iHfhZguIE9At1YsZifgtosvY7i552piKXQQmrC9yIEKHE&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

14) Lu, Thomas, and Marc Rothenberg. "Bone Marrow Derived Eosinophil Cultures". BIO-PROTOCOL, vol 4, no. 12, 2014. Bio-Protocol, LLC, [https://doi.org/10.21769/bioprotoc.1161](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.21769%2Fbioprotoc.1161%3Ffbclid%3DIwAR3j9xSSR_p3T72ohjWa8LVLaJ40AybUgVoUWu1V66dW8gQC--nSA1MrW_4&h=AT2jNfwmv9EsymouyBzpV9TzeOfSwIbGXekE00W9pe6lC81ArPQUYOufcx5jUaDLflj5MFIBo4thQ0xjz6TtPgwsUzxtO9roJzfHd5RHC7KUHz5fto-DhSXKAqmg1gXJrLIGLbkknXO2SZZ6SujiP1o&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

15) Vanden Bempt, M et al. "Generation Of The Fip1l1–Pdgfra Fusion Gene Using CRISPR/Cas Genome Editing". Leukemia, vol 30, no. 9, 2016, pp. 1913-1916. Springer Science And Business Media LLC, [https://doi.org/10.1038/leu.2016.62](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1038%2Fleu.2016.62%3Ffbclid%3DIwAR2wRwT-HaRRXX11UJWIHJ5tnXPN8Y1foe7dnPsqe9v8XTiC38fISTnwITM&h=AT1cTFbZpbd7mSA3Ba0fJkdDUqfVzUTcghdD7f0mAPCtbFz1x8JNO-n5wnYKTK6BU1DhMyEMqaZ1J8J1nrxisF8Qk486QpM6uCbQEQiOhbd7fbpRDdRPRBcrj22hytef4omNEXKt7a6cHKt_5rcOXEY&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

16) Wang, Yueyang et al. "A Robust And Flexible CRISPR/Cas9-Based System For Neutrophil-Specific Gene Inactivation In Zebrafish". Journal Of Cell Science, vol 134, no. 8, 2021. The Company Of Biologists, [https://doi.org/10.1242/jcs.258574](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1242%2Fjcs.258574%3Ffbclid%3DIwAR3bPn5WqE4g01FgCIdL3H73HkqH2EQCkYTtY2vpQFNCCclciondVn6nHrA&h=AT0U0d8Y3KrGl49xAKeew1f5nGb1zFkQrYRDD816R0QGiEEoMRs4fbyAtcB7gLJrXDgHFTgq1alHjyoc1k1ZR0OSVYIYLTc8aU5218tQtjqRiSa0ssPffX63Zy_UC53euPGihmvVMVZE98PNnImWugk&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

17) Knights, Alexander J. et al. "Eosinophil Function In Adipose Tissue Is Regulated By Krüppel-Like Factor 3 (KLF3)". Nature Communications, vol 11, no. 1, 2020. Springer Science And Business Media LLC, [https://doi.org/10.1038/s41467-020-16758-9](https://l.facebook.com/l.php?u=https%3A%2F%2Fdoi.org%2F10.1038%2Fs41467-020-16758-9%3Ffbclid%3DIwAR2j1k1fYRfkJeJJW3BKtc8wBDgN_3XBMvzXdoFlRpvaDTCY_vuc4MAFx4U&h=AT31g8YUaCUpL-W5k26ItaAfUfPsh5sAp3o0kV_-5aDfDpOS7k4p68E-lw1y0T0mqU8GLQatR1T2Zhlcl_ugRhB-jg9kdaqgUC54v--8j_3PAA7Bqf3R5X6gJvODGYYNYTh4I3HFRxn4A9mbx07bi8I&__tn__=-UK-R&c%5B0%5D=AT2vcatlVIdehBh7SYeuajYEmabv5qUNFkg2T_0HxNoHQlunYz5hlEuOATxhOhlSYHBuwuU8JDJuDVfDouyUOs7QHfdcOCInhtKbfmD67A6mINIKnzJEmT0cfk0sVyyMKN77qvJIkAk8FzSx4LoerQxZu1gqNj0pIhC8fJBeuDHvc7NW2i6TtA).

18) Stone, Kelly D et al. “IgE, mast cells, basophils, and eosinophils.” The Journal of allergy and clinical immunology vol. 125,2 Suppl 2 (2010): S73-80. doi:10.1016/j.jaci.2009.11.017

19) Ishimitsu T, Torisu M. “The role of eosinophil chemotactic factor in localized tissue eosinophilia by parasitic infection”. Nihon Rinsho. 1993 Mar;51(3):675-80. Japanese. PMID: 8492442.

20) Mathieu MC, Sawyer N, Greig GM, Hamel M, Kargman S, Ducharme Y, Lau CK, Friesen RW, O'Neill GP, Gervais FG, Therien AG. The C3a receptor antagonist SB 290157 has agonist activity. Immunol Lett. 2005 Sep 15;100(2):139-45. doi: 10.1016/j.imlet.2005.03.003. Epub 2005 Mar 25. PMID: 16154494

21) Fettrelet T, Gigon L, Karaulov A, Yousefi S, Simon H-U. The Enigma of Eosinophil Degranulation. International Journal of Molecular Sciences. 2021;

22(13):7091. [https://doi.org/10.3390/ijms22137091](https://doi.org/10.3390/ijms22137091?fbclid=IwAR3vZ12q9jb8Q3Hs1iX3URCgnCK3mKHADPFBgn5TrmpmufDUPV6WdD3bvME)

22) Gruijs M, Sewnath CAN, van Egmond M. Therapeutic exploitation of neutrophils to fight cancer. Semin Immunol. 2021 Oct;57:101581. doi: 10.1016/j.smim.2021.101581. Epub 2021 Dec 23. PMID: 34922817.

23) Grisaru-Tal S, Dulberg S, Beck L, Zhang C, Itan M, Hediyeh-Zadeh S, Caldwell J, Rozenberg P, Dolitzky A, Avlas S, Hazut I, Gordon Y, Shani O, Tsuriel S, Gerlic M, Erez N, Jacquelot N, Belz GT, Rothenberg ME, Davis MJ, Yu H, Geiger T, Madi A, Munitz A. Metastasis-Entrained Eosinophils Enhance Lymphocyte-Mediated Antitumor Immunity. Cancer Res. 2021 Nov 1;81(21):5555-5571. doi: 10.1158/0008-5472.CAN-21-0839. Epub 2021 Aug 24. PMID: 34429328.

24) Ian L. Linde Tyler R. Prestwood Jingtao Qiu Lorna L. Tolentino Wen-Chao Song Edgar G. Engleman. Neutrophil-activating therapy for the treatment of cancer. January 26, 2023. DOI:<https://doi.org/10.1016/j.ccell.2023.01.002>

25) Caratelli S, Sconocchia T, Arriga R, Coppola A, Lanzilli G, Lauro D, Venditti A, Del Principe MI, Buccisano F, Maurillo L, Ferrone S, Sconocchia G. FCγ Chimeric Receptor-Engineered T Cells: Methodology, Advantages, Limitations, and Clinical Relevance. Front Immunol. 2017 Apr 27;8:457. doi: 10.3389/fimmu.2017.00457. PMID: 28496440; PMCID: PMC5406408.

26) Keven Hoerster, Markus Uhrberg, Constanze Wiek, Peter A. Horn, Helmut Hanenberg, Stefan Heinrichs. HLA Class I Knockout Converts Allogeneic Primary NK Cells Into Suitable Effectors for “Off-the-Shelf” Immunotherapy Front. Immunol., 29 January 2021 Sec. Alloimmunity and Transplantation Volume 11 - 2020 | <https://doi.org/10.3389/fimmu.2020.586168>

27) Rohaan MW, Borch TH, van den Berg JH, Met Ö, Kessels R, Geukes Foppen MH, Stoltenborg Granhøj J, Nuijen B, Nijenhuis C, Jedema I, van Zon M, Scheij S, Beijnen JH, Hansen M, Voermans C, Noringriis IM, Monberg TJ, Holmstroem RB, Wever LDV, van Dijk M, Grijpink-Ongering LG, Valkenet LHM, Torres Acosta A, Karger M, Borgers JSW, Ten Ham RMT, Retèl VP, van Harten WH, Lalezari F, van Tinteren H, van der Veldt AAM, Hospers GAP, Stevense-den Boer MAM, Suijkerbuijk KPM, Aarts MJB, Piersma D, van den Eertwegh AJM, de Groot JB, Vreugdenhil G, Kapiteijn E, Boers-Sonderen MJ, Fiets WE, van den Berkmortel FWPJ, Ellebaek E, Hölmich LR, van Akkooi ACJ, van Houdt WJ, Wouters MWJM, van Thienen JV, Blank CU, Meerveld-Eggink A, Klobuch S, Wilgenhof S, Schumacher TN, Donia M, Svane IM, Haanen JBAG. Tumor-Infiltrating Lymphocyte Therapy or Ipilimumab in Advanced Melanoma. N Engl J Med. 2022 Dec 8;387(23):2113-2125. doi: 10.1056/NEJMoa2210233. PMID: 36477031.

28) De Marco RC, Monzo HJ, Ojala PM. CAR T Cell Therapy: A Versatile Living Drug. Int J Mol Sci. 2023 Mar 27;24(7):6300. doi: 10.3390/ijms24076300. PMID: 37047272; PMCID: PMC10094630.

29) Five-Year Survival with Combined Nivolumab and Ipilimumab in Advanced Melanoma J. Larkin, V. Chiarion‑Sileni, R. Gonzalez, J.-J. Grob, P. Rutkowski, C.D. Lao, C.L. Cowey, D. Schadendorf, J. Wagstaff, R. Dummer, P.F. Ferrucci, M. Smylie, D. Hogg, A. Hill, I. Márquez‑Rodas, J. Haanen, M. Guidoboni, M. Maio, P. Schöffski, M.S. Carlino, C. Lebbé, G. McArthur, P.A. Ascierto, G.A. Daniels, G.V. Long, L. Bastholt, J.I. Rizzo, A. Balogh, A. Moshyk, F.S. Hodi, and J.D. Wolchok. N Engl J Med 2019;381:1535-46. DOI: 10.1056/NEJMoa1910836

30) Laura A Johnson, Carl H June. Driving gene-engineered T cell immunotherapy of cancer. Cell Research volume 27, pages 38–58 (2017). <https://doi.org/10.1038/cr.2016.154>  
<br/>31) Queudeville M, Ebinger M. Blinatumomab in Pediatric Acute Lymphoblastic Leukemia-From Salvage to First Line Therapy (A Systematic Review). J Clin Med. 2021 Jun 8;10(12):2544. doi: 10.3390/jcm10122544. PMID: 34201368; PMCID: PMC8230017.

32) Jabbour, E., Short, N.J., Jain, N. et al. The evolution of acute lymphoblastic leukemia research and therapy at MD Anderson over four decades. J Hematol Oncol 16, 22 (2023). <https://doi.org/10.1186/s13045-023-01409-5>

33) Hagop Kantarjian, M.D., Anthony Stein, M.D., Nicola Gökbuget, M.D., Adele K. Fielding, M.B., B.S., Ph.D., Andre C. Schuh, M.D., Josep-Maria Ribera, M.D., Ph.D., Andrew Wei, M.B., B.S., Ph.D., Hervé Dombret, M.D., Robin Foà, M.D., Renato Bassan, M.D., Önder Arslan, M.D., Miguel A. Sanz, M.D., Ph.D., et al. Blinatumomab versus Chemotherapy for Advanced Acute Lymphoblastic Leukemia. N Engl J Med 2017; 376:836-847 DOI: 10.1056/NEJMoa1609783.

34) Ha GY, Yang SH, Kang HJ, Lee HL, Kim J, Kim YJ, Yu HJ, Lee JI, Jin SH. Comparison of survival outcomes according of patients with metastatic gastric cancer receiving trastuzumab with systemic chemotherapy. Korean J Clin Oncol. 2020 Dec;16(2):63-70. doi: 10.14216/kjco.20011. Epub 2020 Dec 31. PMID: 36945715; PMCID: PMC9942733.

35) Gathirua-Mwangi W, Yang T, Khan T, Wu Y, Afable M. Real-world overall survival of patients receiving cetuximab in later lines of treatment for metastatic colorectal cancer. Future Oncol. 2022 Sep;18(29):3299-3310. doi: 10.2217/fon-2022-0432. Epub 2022 Sep 6. PMID: 36066242.

36) Iriguchi, S., Yasui, Y., Kawai, Y. et al. A clinically applicable and scalable method to regenerate T-cells from iPSCs for off-the-shelf T-cell immunotherapy. Nat Commun 12, 430 (2021). <https://doi.org/10.1038/s41467-020-20658-3>

37) Margo R. Roberts, Keegan S. Cooke, Annie-Chen Tran, Kent A. Smith, Wei Yu Lin, Martin Wang, Thomas J. Dull, Deborah Farson, Krisztina M. Zsebo, Mitchell H. Finer; Antigen-Specific Cytolysis by Neutrophils and NK Cells Expressing Chimeric Immune Receptors Bearing ζ or γ Signaling Domains. _J Immunol_ 1 July 1998; 161 (1): 375–384. <https://doi.org/10.4049/jimmunol.161.1.375>

38) Gross G, Waks T, Eshhar Z. Expression of immunoglobulin-T-cell receptor chimeric molecules as functional receptors with antibody-type specificity. Proc Natl Acad Sci U S A. 1989 Dec;86(24):10024-8. doi: 10.1073/pnas.86.24.10024. PMID: 2513569; PMCID: PMC298636.

39) ClinicalTrials.gov. U.S. National Library of Medicine (US), National Institutes of Health (NIH), \[1/11/2025\]. <https://clinicaltrials.gov/>

Data Availability

I, Jeremy Stubbs, attest that all data used in the manuscript is open-source.
