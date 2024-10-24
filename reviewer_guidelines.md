---
title: Reviewer Guidelines
layout: default
weight: 6
hide: false
---

# AISTATS 2025 Reviewer Guidelines

This page provides guidelines for reviewers for AISTATS 2025. The guideline is based on previous AISTATS conferences’ practise.

## Responsibilities of a Reviewer

1. Report problematic papers to the Area Chair (e.g., unacceptable formatting issues, dual submissions, plagiarism, etc. ); see [this FAQ]({{ "ac_guidelines.html#frequently-asked-questions" | relative_url }}) for a list of issues that may arise.
2. Submit high-quality reviews.
3. During the rebuttal period, discuss with the other reviewers and the AC to help arrive at a good decision.
4. Recommend papers for oral talks, awards, etc..

## Important Dates

Dates may be subject to change. All deadlines are AoE timezone.

  - Abstract deadline: **Thursday, 3 October, 2024**
  - Start bidding: **Tuesday, 8 October, 2024**
  - Paper submission deadline: **Thursday, 10 October, 2024**
  - Bidding deadline: **Thursday, 17 October, 2024**
  - Appendix submission deadline: **Thursday, 17 October, 2024**
  - Review period: **Tuesday, 22 October - Tuesday, 19 November, 2024**
  - Discussion period: **Friday, 6 December - Thursday, 19 December, 2024**
  - Paper decision notifications: **Tuesday, 21 January, 2025**
  

## How to Review?

The purpose of the review process is twofold. First, to identify papers which offer significant contributions to the fields of artificial intelligence and statistics, for attendees and readers. Second, to provide constructive feedback to authors that they can use to improve their work. Your role as a reviewer is vital to both goals.

When reviewing a paper, always think about the impact the work may have on the community in the long run: out-of-the-box ideas, novel problems, and "bridging fields" contributions are crucial for the successful development of the field, so do not neglect the importance of papers with this type of contributions. Novel or interdisciplinary works are often very easy to criticize, because, for example, the assumptions they make or the models they use are not yet widely accepted by the community. Yet, such works may be of high importance for the progress of the field in the long run, so please try to be aware of this bias, and avoid dismissive criticism.

_Acknowledgments: The guidelines in this document are partially adopted from the AISTATS 2023 reviewer guidelines, which in turn utilize reviews written for some AISTATS, NeurIPS, ICML, and ICLR papers._


## Review Form and Guidelines for Writing a Good Review

The review form will ask you for the following:

1. **Summary And Contributions:**

    Briefly summarize the paper motivation, key contributions and achievements in a paragraph. Although this part of the review may not provide much new information to authors, it is invaluable to ACs and program chairs, and it can help the authors determine whether there are misunderstandings that need to be addressed in their author response. There are many examples of contributions that warrant publication at AISTATS. These contributions may be theoretical, methodological, algorithmic, empirical, connecting ideas in disparate fields ("bridge papers"), or providing a critical analysis (e.g., principled justifications of why the community is going after the wrong outcome or using the wrong types of approaches.).

2. **Paper Keywords:**

    Provide 3 keywords about the paper's topic.

3. **Expertise Keywords:**

    Proivde 3 keywords about your research expertise.

    The purpose for setting up these 2 questions is to allow the Area Chairs to evaluate whether the reviewer's expertise matches the submission's research topic. If you notice a discrepancy between your answers to these two questions, this may indicate expertise mismatch, and in this case we suggest you consider putting a lower confidence score later. 

4. **Soundness:**

    - Correct
    - Minor errors  (e.g., typo or errors that do not affect the main results)
    - Major errors or trivial results (e.g., an incorrect theorem, or known results)
    - Not applicable

    Please assess the soundness of the paper by selecting one of the options above.

5. **Soundness Justification:**

    Justification for your provided judgment of soundness. If not applicable, put in “N/A”. If your choice is “minor errors” or “major errors”, please specify the details of your concerns.

    These two questions mainly evaluate the paper's soundness in terms of theoretical contributions if applicable. Incorrect claims or methodology are the primary reasons for rejection. Your comments should be detailed, specific, and polite. Please avoid vague, subjective complaints. Thoroughly motivate your criticism so that authors will understand your point of view and potentially respond to you. Remember to provide appropriate references if relevant.

    Example comments:
    
    (1) "Theorem 3.1 contains major errors: the proved convergence rate in line XXX is missing a factor of T^1/3 since [reason for this claim]. Because of this, the correct convergence rate of the proposed algorithm is no better than the baseline method YYY (citation 1)."
    
    (2) "Lemma 4.2 contains minor errors: the time complexity figure in line XXX should be O(YYY) instead of O(ZZZ) because [reason for this claim], although this does not affect the final complexity figure too much when combining all algorithmic components together."

    Note that unless the assumptions are very unrealistic and much stronger than those of similar theoretical results in the literature (please justify in detail), otherwise we recommend commenting on the potential issues about assumptions in the additional comments.

6. **Significance:**

    - Significant with well supported statistical metrics and appropriate baselines
    - Somewhat significant (e.g., significant performance in some but not all experiments, missing a baseline)
    - Not significant (e.g., overall similar to baselines, missing many baselines)
    - Not applicable

    Please assess the significance of the paper by selecting one of the options above.
    
7. **Significance Justification:**

    Justification of your provided judgment of significance. If not applicable, put in “N/A”. If your choice is “somewhat significant” or “not significant”, please specify the details of your concerns.

    These two questions mainly evaluate the paper's significance in terms of empirical results if applicable. Your comments should be detailed, specific, and polite. Please avoid vague, subjective complaints. Thoroughly motivate your criticism so that authors will understand your point of view and potentially respond to you. Remember to provide appropriate references if relevant.

    Example comments:

    "The proposed method outperforms the selected baselines significantly. However, method XXX has not been added to comparison which hinders the significance of the results. Method XXX should be an appropriate baseline to compare with because [describe the reason, e.g., method XXX differs from the proposed method only in aspect YYY]."

8. **Novelty:**

    - Ground-breaking new results
    - New results
    - Incremental compared to existing results
    - Known results, or trivial extension of known results

    Please assess the novelty of the paper by selecting one of the options above.

9. **Novelty Justification:**

    Justification of your provided judgment of novelty. If your choice is “incremental” or “known results” please specify the previous publication(s) that support your choice.

    Another important axis is the significance and the novelty of the contributions relative to what has been done already in the literature, and here you may want to cite these relevant prior works. Try to find positive aspects, irrespective of your overall (positive or negative) assessment. One measure of the significance of a contribution is (your belief about) the level to which researchers or practitioners will make use of or be influenced by the proposed ideas. Solid, technical papers that explore new territory or point out new directions for research are preferable to papers that advance the state of the art, but only incrementally. Do *not* use criteria such as "the paper's research area is important" or "the paper is well-written" since these aspects are too generic and commonly occur in poor reviews.

    Example comments:
    
    "The proposed method combines training method XXX (citation 1) and sampling method YYY (citation 2) in order to achieve better performance on metric ZZZ. The combination is done by running the sampling step in XXX using sampler YYY, while in the literature the choices of the sampler are usually e.g., AAA (citation 3) and BBB (citation 4). Although combinatorial, this paper is the first one to show that sampler YYY can work in the context of model CCC (citation 5) trained with method XXX."

10. **Non-conventional Contributions:**

    Does the submission contain non-conventional research contributions? Examples: novel ideas with not widely accepted assumptions, new problems and/or tasks, “bridging fields” contributions.

    Some submissions may contain out-of-the-box ideas, novel problems, and "bridging fields" contributions are crucial for the successful development of the field, so do not neglect the importance of papers with this type of contributions. If applicable, you can comment on non-conventional aspects regarding the submission's assumptions, model designs and methods, especially if they are not yet widely accepted by the relevant research community.

11. **Clarity:**

    Is the paper clearly written? Is it well organized? (If not, please make constructive suggestions for improving its clarity.)

    Consider whether the paper has clearly (1) stated its contributions, notation and results, (2) explained the meaning of the theoretical assumptions, and/or (3) motivated the proposed methodology well with e.g., examples. Note that a superbly written paper provides enough information for an expert reader to reproduce its results. 

12. **Relation To Prior Work:**

    - All related works are clearly discussed
    - All related works cited but the discussion is less clear
    - Some minor related works are missing or described incorrectly
    - Some important related works are missing or described incorrectly

    We recommend you to explain in the Additional Comments field whether the submission is written with due scholarship and suitably relates the proposed work to prior work in the literature. The related work section should not just list prior work, but explain how the proposed work differs from, builds upon, and/or improves on it. Note that authors are not expected to know about all non-peer-reviewed work (e.g, preprints such as on arXiv). Other works (whether peer-reviewed or not) that appeared less than 4 months before the paper submission deadline (i.e., after **Monday, June 10, 2024**), are considered concurrent to AISTATS submissions; authors are not obligated to make detailed comparisons to such papers (though, especially for the camera ready versions of accepted papers, authors are encouraged to).

13. **Additional Comments (Optional):**

    Add your additional comments, feedback and suggestions for improvement, as well as any further questions for the authors. what would you do differently if you were given the chance to improve the paper? Again, please avoid vague, subjective complaints. Think about the times when you received an unfair, unjustified, short, or dismissive review. Try not to be that reviewer! Always be constructive and help the authors understand your viewpoint, without being dismissive or using inappropriate language. Remember that you are not reviewing your level of interest in the submission, but its scientific contribution to the field!

14. **Reproducibility:**

    - Sufficient amount of details available for reproducing the main results
    - Some amount of details available
    - Insufficient amount of details available
    - Not applicable (the paper does not have experiments)

    Are there enough details to reproduce the main experimental results of this work? Please assess whether, with the information provided by the authors in the paper and the supplementary material, the assumptions, experimental settings and limitations of this work are clearly stated. If they are not, consider listing this as a weakness of the paper in the additional comments.

15. **Rating:**

    - 5: Top 10% of accepted papers
    - 4: Accept
    - 3: Borderline accept
    - 2: Borderline reject
    - 1: Reject

    You should NOT assume that you were assigned a representative sample of submissions, nor should you adjust your scores to match the overall conference acceptance rates. The "Rating" for each submission should reflect your assessment of the submission's contributions.

16. **Confidence:**

    - 5: Absolutely certain (Use this sparingly; please ensure you are very familiar with the related work, you have carefully checked and understood the proofs and/or experimental details if applicable)
    - 4: Confident, but not absolutely certain. (It is unlikely, but not impossible, that you did not understand some parts of the submission or that you are unfamiliar with some pieces of related work.)
    - 3: Fairly confident (It is possible that you did not understand some parts of the submission or that you are unfamiliar with some pieces of related work. Math/other details were not carefully checked.)
    - 2: Somewhat confident (You are willing to defend your assessment, but it is quite likely that you did not understand central parts of the submission or that you are unfamiliar with some pieces of related work. Math/other details were not carefully checked.)
    - 1: Educated guess (The submission is not in your area or the submission was difficult to understand. Math/other details were not carefully checked.)

    When answering this question, you might want to compare your answers in Paper Keywords and Expertise Keywords, and consider whether in this particular case you are absolutely certain with your judgment.


17. **Ethical Concerns:**

    - No concern
    - Minor concerns
    - Major concerns

    Does the submission raise potential ethical concerns? Does this submission raise potential ethical concerns? These include methods, applications or data that create or reinforce unfair biases and/or that have a primary purpose of harm or injury.


18. **Ethical Concern Justification:**

    Justification of your provided judgment of ethical concerns. If not applicable, put in “N/A”.

    Please assess whether the paper discusses the potential negative societal impact and/or ethical issues of the work. If not, please assess if the paper should include this point due to the nature of the research topic or ideas.

    Note that your overall rating of this paper should be independent of this ethics assessment. Your duty here is to flag papers that might need additional review from the ethical perspective.

19. **Code of Conduct:**

    Agree to abide by the AISTATS code of conduct. The AISTATS code of conduct can be found here: [AISTATS Code of Conduct](http://aistats.org/aistats2025/code-of-conduct.html)

20. **Confidentiality Agreement:**

    Reviewers must keep the paper and supplementary materials (including code submissions and LaTeX source), as well as the reviews, confidential. This includes deleting any submitted code at the end of the review cycle to comply with confidentiality requirements.

21. **Confidential Comment (Optional):**

     If you have comments that you wish to be kept confidential from the authors, you can use this field to leave confidential comments for the Area Chair. Such comments might include explicit comparisons of the submission to other submissions, minor formatting issues, and criticisms that are more bluntly stated. If you accidentally find out the identities of the authors, please do not divulge the identities to anyone.


## Best Practices

+ **Be thoughtful.** The paper you are reviewing may have been written by a first
year graduate student who is submitting to a conference for the first time and you
don't want to crush their spirits.

+ **Be fair.** Do not let personal feelings affect your review.

+ **Be useful.** A good review is useful to all parties involved: authors, other
reviewers, and area chairs.

+ **Be specific.** Do not make vague statements in your review, as they are
unfairly difficult for authors to address.

+ **Be flexible.** The authors may address some points you raised in your review
during the discussion period. Make an effort to update your understanding of the
paper when new information is presented, and revise your review to reflect this.

+ **Be timely.** Please respect the deadlines and respond promptly during the
discussion.  If you cannot complete your review on time, please let the Area Chair
know as soon as possible.

If someone pressures you into providing a positive or negative review for a
submission, please notify the Program Chairs right away at
[aistats2025conference@gmail.com](mailto:aistats2025conference@gmail.com).

If you notice unethical or suspect behavior, please notify your Area Chair right
away.

## LLM Policy

The use of LLMs is not allowed to write papers, reviews, and meta-reviews. They can be used as an assist tool, for example, to check grammatical issues. Ultimately, you are responsible for the text you write, including content generated by LLMs that could be construed as plagiarism or scientific misconduct (e.g., fabrication of facts). Similar to other ML venues, at AISTATS too, LLMs are not eligible for authorship.


## Other Remarks

1. **Minor formatting issues.** You may find papers with minor formatting issues such as different citation styles. We have decided not to desk-reject these papers and ask you to disregard such minor formatting issues in your reviews (please flag them but do not change your score/evaluation). We will take them into account and ensure the correct style is used if the paper gets accepted.

2. **Supplement.** It is explicitly allowed to append supplementary material to the manuscript (after the citations). As there is a separate submission deadline for supplementary material, it is the authors' responsibility that the supplementary material appended to the manuscript and the one uploaded separately do not conflict in their content. As stated in the [Call for Papers]({{ "call-for-papers.html" | relative_url }}), looking at the supplementary materials is optional to evaluate the submission. *Update September 20, 2024*: Should the supplementary material added to the manuscript and the one uploaded separately conflict in their content, reviewers are free to consider either version of the material for their review (supplementary material is still optional for the review).

3. **Links in submission.** Some submissions may contain links (e.g., URL) to external materials such as code. We wish to emphasize that we cannot guarantee the safety of such external links. Our general recommendation is that you not follow such links and simply take it as a statement from the authors that they are ready to make such material available if the paper is accepted. If you decide to access a link, be aware it might reveal that you have consulted the linked site, and thus potentially reveal that you are involved in the reviewing of the paper.

4. **Code in Github.** Some of the papers assigned to you may have submitted code. Note that, as for any supplementary material, reviewing such additional information (e.g., code) is optional. When accessing anonymous Github links submitted by authors, please make sure to directly download the code or clone the repository after logging out of your own Github account; please do not fork the repository as this might reveal your identity to the authors. Note also that any submitted code may contain security vulnerabilities.
