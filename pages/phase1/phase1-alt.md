---
title: Assessment
layout: page
permalink: /phases/1-alt/
sidenav: playbook

## scripts:
##  - ../../assets/playbook/js/assessment-app.js

---

# Phase 1 - Problem Assessment

**Note:** This is a notional table and the level of importance associated with each question may be tied to the use case being assessed. Assign Points based on the Attribute Importance Rank (with suggested weighting). You may adjust the weight of questions as they apply to your use case. (5 – critical, 4 – very high, 3 – high, 2 – moderate, 1 – slightly, 0 – not at all) 

<form lpformnum="1">
    <div id="assessment-app">
    <div class="assessments">    
        <ol>
            {% for quest in site.data.phase1-scorecard.questions-alt %}
            <li>
                <b>{{quest.question-title}}</b> {{quest.question-description}}
                <br/>
                <fieldset class="usa-fieldset-inputs usa-offset-one-twelfth">    
                    <ol class="usa-unstyled-list">
                        {% for rb in quest.values %}
                        <li class="answer">
                            <input id="{{ rb.id }}" type="radio" onclick="updateResult()" name="{{ quest.question }}" value="{{rb.value}}" {% if rb.checked %} checked {% endif %}>
                            <label for="{{ rb.id }}">{{ rb.label }}</label>
                        </li>
                        {% endfor %}
                    </ol>
                </fieldset>
            </li>
            {% endfor %}
        </ol>
    </div>

<h3> Results </h3>
Provided here are common questions and relative weights for answers to serve as a preliminary guide for those considering a blockchain approach. While useful, this is still only a guide for consideration and further investigation. Sound engineering analysis and practices should still prevail. 

<b>Score Groupings:</b> In order to assess the applicability of a blockchain approach, we have grouped scores to guide the reader to where taking a blockchain approach would be most      beneficial (highest score) and where it is less likely (but still may be applicable, just needs more scrutiny).

<div class="results">
    <h3 id="total">Total: xx points</h3>
    <p style="">
        Provided here are common questions and relative weights for answers to serve as a preliminary guide for those considering a blockchain approach. While useful, this is still only a guide for consideration and further investigation. Sound engineering analysis and practices should still prevail.<br/>
        <b>Score Groupings:</b> In order to assess the applicability of a blockchain approach, we have grouped scores to guide the reader to where taking a blockchain approach would be most beneficial (highest score) and where it is less likely (but still may be applicable, just needs more scrutiny).
    </p>
    <h4 id="grouping--15-20-total-points" style="">Score (-15 - 20 total points)</h4>
    <p style="">A score of 20 or below typically represents a small ROI and limited applicability from a blockchain approach. Consider that while the score may be low, your situation may still warrant deeper analysis as there can be a compelling reason to continue with a blockchain approach that did not fall into the standard categorization.</p>
    <h4 id="grouping-21-40-total-points" style="">Score (21 - 40 total points)</h4>
    <p style="display: none;">A score of between 21 and 40 could typically be supported with a blockchain approach but isn’t an overwhelming natural candidate. These situations can have powerful reasons that can still drive a blockchain approach, yet they might also have mitigating factors that make a traditional approach a better alternative. In these situations, a more thorough analysis is typically needed.</p>
    <h4 id="grouping-41-50-total-points" style="">Score (41 - 50 total points)</h4>
    <p style="display: none;">A score above 41 typically represents a compelling ROI and strong applicability that would benefit significantly from a blockchain approach. It is strongly recommended to consider the costs and benefits of a blockchain approach in these instances while still considering other additive and mitigating factors in the organization, strategic direction, interdependencies, and related items</p>
</div>
</div>
</form>

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha256-k2WSCIexGzOj3Euiig+TlR8gA0EmPjuc79OEeY5L45g=" crossorigin="anonymous">
</script>
<script src="/blockchain-playbook/assets/playbook/js/assessment-app.js" async></script>