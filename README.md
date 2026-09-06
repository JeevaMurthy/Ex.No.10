
<body>
<div class="page">

<div class="header">
    <h1>Ex.No.10 – Prompt Engineering for Real-world Engineering Application</h1>
    <div>Capstone Mini Project – Robotics Engineering</div>
</div>

<strong>Registration No.</strong><span>212223230090</span>


<h2>Aim</h2>
<p>
To demonstrate how various prompting techniques can be applied to a real-world engineering application
by designing, refining, evaluating, and presenting AI-generated technical content for a selected robotics project.
The experiment focuses on using structured prompt patterns to improve content quality, coherence, accuracy,
relevance, readability, and engineering usefulness.
</p>

<h2>Engineering Domain Selected</h2>
<p><strong>Robotics</strong></p>

<h2>Selected Project</h2>
<p><strong>RoboAssist – AI-Based Robotic Maintenance Assistant</strong></p>

<p>
RoboAssist is a prompt-engineering-based decision-support concept for industrial robotic systems.
It assists maintenance teams by converting equipment observations, maintenance records, and reported symptoms
into structured technical content such as maintenance case studies, inspection summaries, troubleshooting articles,
and technician-oriented documentation.
</p>

<div class="note">
<strong>Project Scope:</strong> RoboAssist is designed as an AI-assisted documentation and decision-support concept.
It does not replace qualified robotics or maintenance engineers, manufacturer manuals, safety procedures, or
authorized maintenance decisions.
</div>

<h2>Problem Statement</h2>
<p>
Industrial robotic systems contain motors, gearboxes, joints, controllers, end effectors, sensors, cables,
and communication interfaces. When abnormal behaviour occurs, such as unexpected vibration, reduced accuracy,
joint noise, temperature rise, repeated position errors, or communication faults, maintenance teams must identify
possible causes and document the situation clearly.
</p>

<p>
Manual preparation of technical reports, troubleshooting documents, case studies, and training material can be
time-consuming and inconsistent. At the same time, generic AI prompts can produce vague explanations, omit
important engineering context, or present unsupported claims. This project addresses the documentation gap by
using structured prompt patterns to generate two forms of robotics content:
</p>

<ol>
    <li><strong>Case Study</strong> – documenting an industrial robot maintenance scenario.</li>
    <li><strong>Technical Article</strong> – explaining predictive maintenance for robotic systems to undergraduate engineering students.</li>
</ol>

<h2>Selected Content Generation Scenarios</h2>
<ol>
    <li><strong>Case Study</strong> – “RoboAssist: AI-Assisted Predictive Maintenance for an Industrial Robotic Arm”</li>
    <li><strong>Technical Article</strong> – “Predictive Maintenance in Industrial Robotics: Using AI as a Maintenance Decision-Support Tool”</li>
</ol>

<h2>Prompt Patterns Used and How They Were Applied</h2>

<table>
<tr><th>Pattern</th><th>Application in This Experiment</th></tr>
<tr>
<td><strong>Query Decomposition</strong></td>
<td>The broad request to create robotics content was divided into smaller parts such as system background, robot components, symptoms, possible causes, maintenance workflow, challenges, and future scope.</td>
</tr>
<tr>
<td><strong>Decision Making</strong></td>
<td>The AI model was asked to select the most suitable narrative angle and prioritize the most relevant engineering factors before generating the final content.</td>
</tr>
<tr>
<td><strong>Answer Engineering</strong></td>
<td>Specific instructions were given for headings, paragraph length, tables, technical terminology, audience level, and output structure.</td>
</tr>
<tr>
<td><strong>Fact Check List</strong></td>
<td>The model was instructed to identify technical claims that require verification from equipment manuals, maintenance logs, datasheets, standards, or engineering references.</td>
</tr>
<tr>
<td><strong>Tail Generation</strong></td>
<td>The initial case study was extended with lessons learned, recommended documentation practices, and a future roadmap.</td>
</tr>
<tr>
<td><strong>Menu Actions</strong></td>
<td>The AI was given multiple possible writing approaches and asked to select the most appropriate one for the intended audience.</td>
</tr>
<tr>
<td><strong>Semantic Filter</strong></td>
<td>The final article was filtered for clarity, relevance, moderate technical depth, non-exaggerated claims, and an undergraduate-friendly tone.</td>
</tr>
</table>

<h2>Procedure</h2>

<h3>Step 1: Select the Engineering Domain</h3>
<p>
Robotics was selected because industrial robotic systems contain multiple interacting mechanical, electrical,
control, and software components, making them suitable for structured engineering documentation.
</p>

<h3>Step 2: Define the Project</h3>
<p>
The RoboAssist concept was defined as an AI-assisted maintenance documentation and decision-support workflow for
industrial robotic arms.
</p>

<h3>Step 3: Select Two Content Scenarios</h3>
<p>
A maintenance case study and a technical article were selected so that the effect of prompt patterns could be
demonstrated using two different communication formats.
</p>

<h3>Step 4: Generate the First Draft</h3>
<p>
A simple prompt was used to create a generic first draft. The limitations of the draft were then identified.
</p>

<h3>Step 5: Apply Query Decomposition</h3>
<p>
The broad topic was divided into smaller content requirements to improve organization and coverage.
</p>

<h3>Step 6: Apply Decision Making</h3>
<p>
The AI model was asked to select and prioritize the most suitable technical and communication approach.
</p>

<h3>Step 7: Apply Answer Engineering</h3>
<p>
The desired structure, audience, word limits, headings, tables, and writing style were explicitly defined.
</p>

<h3>Step 8: Apply Fact Check List</h3>
<p>
Technical claims such as component behaviour, fault causes, maintenance recommendations, and performance statements
were identified for verification before practical use.
</p>

<h3>Step 9: Apply Tail Generation and Semantic Filtering</h3>
<p>
Additional useful sections were generated and the complete content was refined to remove repetition, irrelevant
material, unsupported certainty, and excessive jargon.
</p>

<h3>Step 10: Evaluate the Final Output</h3>
<p>
The generated content was evaluated using coherence, creativity/originality, accuracy, relevance, tone and style,
readability, structure, and overall usefulness.
</p>

<h2>Content 1: Case Study – RoboAssist: AI-Assisted Predictive Maintenance for an Industrial Robotic Arm</h2>

<h3>Basic Prompt (First Draft)</h3>
<pre>Write a short case study about using AI to support maintenance of an industrial robotic arm.</pre>

<h3>Sample Output (First Draft)</h3>
<p>
An industrial robotic arm developed a maintenance issue during production. AI was used to analyze the reported
symptoms and provide possible causes. The system helped the maintenance team organize the inspection process and
document the issue. The case showed that AI can support robotic maintenance activities.
</p>

<p><strong>Observation:</strong> The draft is generic. It does not define the robot, symptoms, maintenance context,
evidence, validation requirements, or the structure of the case study.</p>

<h3>Refined Prompt (Query Decomposition + Fact Check List)</h3>
<pre>
Before writing, list the factual and engineering claims that should be checked.

Project:
RoboAssist – AI-Based Robotic Maintenance Assistant.

Scenario:
A six-axis industrial robotic arm used on an automated assembly line has reported increased vibration
during one joint movement, occasional positioning error, and abnormal mechanical noise.

Available project information:
- Six-axis industrial robotic arm
- Automated assembly application
- Vibration reported around one joint
- Occasional positioning error
- Intermittent abnormal mechanical noise
- Maintenance history must be verified before diagnosis
- Manufacturer documentation must be consulted for component-specific limits

Then write a 350-word case study covering:
1. Background
2. System Overview
3. Maintenance Scenario
4. AI-Assisted Analysis
5. Verification Process
6. Lessons Learned
7. Future Scope

Do not invent manufacturer-specific thresholds, measured failure rates, or confirmed root causes.
Clearly separate observations, hypotheses, and verified findings.
</pre>

<h3>Sample Output (Refined Draft)</h3>
<p>
<strong>Fact list:</strong> six-axis robotic arm, automated assembly application, reported joint vibration,
occasional positioning error, intermittent mechanical noise, need for maintenance-history verification,
and requirement for manufacturer documentation before confirming component limits.
</p>

<p>
<strong>Case Study:</strong> An automated assembly line reported abnormal vibration and intermittent positioning
error in a six-axis industrial robotic arm. RoboAssist organized the reported observations and grouped possible
causes into mechanical, control, sensing, and maintenance categories. Rather than treating an AI-generated
possibility as a confirmed fault, the workflow required the maintenance team to verify historical trends,
inspect the relevant joint, and consult authorized equipment documentation before making a decision.
</p>

<p><strong>Observation:</strong> Listing the known facts before drafting reduced unsupported claims and made the
case study easier to verify.</p>

<h3>Advanced / Final Prompt (Decision Making + Answer Engineering + Tail Generation)</h3>
<pre>
Two possible narrative angles are available for the case study:
(a) Technology-first – explain the robotic system and AI workflow before discussing the maintenance event.
(b) Maintenance-impact-first – begin with the reported machine condition and then explain how RoboAssist
supports investigation.

Choose the angle best suited for maintenance engineers and final-year robotics students and briefly justify it.

Then write a 450–500 word professional case study using this structure:

1. Background
2. Robotic System Overview
3. Maintenance Scenario
4. AI-Assisted Workflow
5. Verification and Human Validation
6. Lessons Learned
7. Future Roadmap

Requirements:
- Clearly distinguish measured observations from assumptions.
- Do not invent manufacturer-specific limits.
- Do not claim that AI confirmed the fault.
- Explain how prompt engineering improves documentation quality.
- Present the maintenance workflow in a concise table.
- Use technical but readable language.
- Avoid exaggerated claims.
</pre>

<h3>Sample Output (Final Version – Abbreviated)</h3>
<p>
<strong>Chosen angle:</strong> Maintenance-impact-first, because the intended audience is more likely to connect
with a real machine condition before examining the supporting AI workflow.
</p>

<p>
<strong>1. Background:</strong> The robotic arm supports automated assembly and is expected to maintain repeatable
positioning throughout production. An increase in vibration, intermittent positioning error, and unusual joint
noise prompted a structured maintenance review.
</p>

<p>
<strong>2. Robotic System Overview:</strong> The system includes a multi-axis mechanical structure, joint actuators,
position feedback, controller, end effector, safety systems, and communication interfaces.
</p>

<table>
<tr><th>Maintenance Stage</th><th>RoboAssist Contribution</th><th>Human Validation</th></tr>
<tr><td>Observation</td><td>Structures reported symptoms</td><td>Maintenance team verifies symptoms</td></tr>
<tr><td>Analysis</td><td>Groups plausible causes</td><td>Engineer checks evidence</td></tr>
<tr><td>Inspection</td><td>Generates organized checklist</td><td>Authorized personnel perform inspection</td></tr>
<tr><td>Documentation</td><td>Produces standardized report</td><td>Engineer approves final record</td></tr>
</table>

<p>
<strong>6. Lessons Learned:</strong> Prompt quality strongly affected how clearly symptoms, hypotheses, and
verification steps were separated. Human review remained essential.
</p>

<p><strong>7. Future Roadmap:</strong> The workflow can be extended with structured sensor histories,
maintenance records, image-based inspection inputs, and organization-specific documentation templates.
</p>

<p><strong>Observation:</strong> Selecting a narrative angle before drafting created a clearer case study, while
tail generation added meaningful lessons learned and future scope instead of ending with a simple summary.</p>

<h2>Content 2: Technical Article – Predictive Maintenance in Industrial Robotics</h2>

<h3>Basic Prompt (First Draft)</h3>
<pre>Write an article about predictive maintenance in industrial robotics.</pre>

<h3>Sample Output (First Draft)</h3>
<p>
Predictive maintenance uses data and technology to identify machine problems before failure occurs. In industrial
robotics it can help monitor motors, joints, vibration, temperature, and other operating conditions. AI can assist
maintenance teams by analyzing information and identifying patterns.
</p>

<p><strong>Observation:</strong> The draft is correct at a general level but is shallow and does not explain how
AI-assisted prompting can support technical communication or why human validation is important.</p>

<h3>Refined Prompt (Menu Actions + Semantic Filter)</h3>
<pre>
Choose the best article angle for final-year engineering students from these options:

1. Pure technical explanation of predictive-maintenance methods
2. Practical engineering explainer using an industrial robotic arm as the central example
3. Short management-focused article about maintenance cost reduction

Select the most suitable angle and explain why.

Then write a 400-word article with the headings:
- Introduction
- What Predictive Maintenance Means
- Application to Industrial Robots
- Role of AI
- Benefits
- Challenges
- Ethical and Safety Considerations
- Future Scope
- Conclusion

Use a balanced technical tone. Explain specialized terms briefly.
Do not invent statistics or manufacturer-specific performance claims.
</pre>

<h3>Sample Output (Refined Draft)</h3>
<p>
<strong>Chosen angle:</strong> Practical engineering explainer using an industrial robotic arm, because it connects
the concept to a concrete engineering system while remaining understandable to students.
</p>

<p>
Predictive maintenance aims to identify developing equipment problems early enough to support planned action.
For industrial robots, relevant information may include vibration trends, temperature changes, actuator behaviour,
positioning consistency, alarms, and maintenance history.
</p>

<p>
AI can help organize such information and generate structured inspection documentation. However, an AI-generated
explanation should be treated as decision support rather than a confirmed diagnosis. Engineering personnel still
need to verify evidence using suitable measurements, documentation, and approved maintenance procedures.
</p>

<p><strong>Observation:</strong> The menu-action step selected a more practical audience angle, while the semantic
filter produced a clearer and more balanced technical explanation.</p>

<h3>Final Version – After Semantic Filter Iteration</h3>

<h4>Semantic Filter Prompt</h4>
<pre>
Rewrite the article above using this semantic filter:
- Keep the practical robotics example.
- Make the opening relatable to an engineering student.
- Keep all technical ideas accurate and appropriately qualified.
- Remove repetition and unnecessary jargon.
- Do not add unsupported statistics.
- Keep the tone informative, balanced, and professional.
- Emphasize that AI supports rather than replaces qualified engineering judgment.
</pre>

<h4>Sample Output – Final Article Excerpt</h4>
<p>
Imagine an industrial robotic arm beginning to show a small change in behaviour: a joint produces an unusual sound,
vibration appears during a repeated motion, and positioning is no longer as consistent as before. A reactive
maintenance process may wait until the problem becomes severe. Predictive maintenance takes a different approach
by examining available condition information and looking for signs that deserve investigation.
</p>

<p>
In industrial robotics, this information can include vibration observations, temperature records, controller alarms,
positioning behaviour, maintenance history, and other verified condition data. AI can help maintenance teams organize
these inputs, group possible causes, prepare inspection checklists, and generate clear technical documentation.
</p>

<p>
The important limitation is that an AI-generated explanation is not the same as a confirmed machine diagnosis.
Qualified personnel must verify the condition and follow approved equipment and safety procedures before maintenance
decisions are made.
</p>

<p><strong>Observation:</strong> The semantic-filter rewrite improved readability and engagement while preserving the
technical boundaries and human-validation requirements.</p>

<h2>AI Output Evaluation</h2>

<table>
<tr>
<th>Content</th><th>Version</th><th>Coherence</th><th>Creativity / Originality</th><th>Accuracy</th><th>Tone &amp; Style</th><th>Overall</th>
</tr>
<tr>
<td>Case Study</td><td>Basic First Draft</td><td>Fair</td><td>Low</td><td>Fair – generic</td><td>Generic</td><td>5.5 / 10</td>
</tr>
<tr>
<td>Case Study</td><td>Refined</td><td>Good</td><td>Moderate</td><td>Good – better grounded</td><td>Neutral</td><td>7.6 / 10</td>
</tr>
<tr>
<td>Case Study</td><td>Final Advanced</td><td>Excellent</td><td>Good</td><td>Excellent – clearly qualified</td><td>Professional</td><td>9.2 / 10</td>
</tr>
<tr>
<td>Article</td><td>Basic First Draft</td><td>Fair</td><td>Low</td><td>Good but shallow</td><td>Generic</td><td>5.2 / 10</td>
</tr>
<tr>
<td>Article</td><td>Refined</td><td>Good</td><td>Good</td><td>Good</td><td>Appropriately technical</td><td>7.8 / 10</td>
</tr>
<tr>
<td>Article</td><td>Final Semantic Filter</td><td>Excellent</td><td>High</td><td>Good</td><td>Clear and balanced</td><td>9.0 / 10</td>
</tr>
</table>

<p>
<strong>Summary:</strong> Across both content types, coherence and accuracy improved most after query decomposition
and fact-check listing. Decision making improved the narrative focus of the case study. Menu actions helped select an
appropriate audience angle for the article. Answer engineering improved structure, tail generation added depth, and
semantic filtering improved readability and relevance.
</p>

<h2>Comparison of Prompt Versions</h2>

<table>
<tr><th>Prompt Version</th><th>Output Quality</th><th>Main Improvement</th></tr>
<tr><td>Basic Prompt</td><td>Basic</td><td>General content with limited engineering context</td></tr>
<tr><td>Query Decomposition</td><td>Good</td><td>Better section coverage and organization</td></tr>
<tr><td>Decision Making</td><td>Better</td><td>More focused narrative and prioritization</td></tr>
<tr><td>Answer Engineering</td><td>Very Good</td><td>Controlled headings, audience, and output format</td></tr>
<tr><td>Fact Check List</td><td>Improved Reliability</td><td>Potentially unsupported claims identified for verification</td></tr>
<tr><td>Tail Generation</td><td>Improved Depth</td><td>Lessons learned and future roadmap added</td></tr>
<tr><td>Semantic Filter</td><td>High</td><td>Repetition and unnecessary jargon reduced</td></tr>
<tr><td>Final Prompt</td><td>High</td><td>Complete, structured, balanced engineering content</td></tr>
</table>

<h2>Evaluation</h2>

<table>
<tr><th>Evaluation Parameter</th><th>Observation</th></tr>
<tr><td>Coherence</td><td>Final content was logically organized and easier to follow.</td></tr>
<tr><td>Accuracy</td><td>Technical claims were treated as verification points rather than unsupported facts.</td></tr>
<tr><td>Creativity / Originality</td><td>Different narrative approaches were explored before selecting the final style.</td></tr>
<tr><td>Relevance</td><td>Semantic filtering removed unrelated and repetitive information.</td></tr>
<tr><td>Readability</td><td>Technical terms were explained using accessible engineering language.</td></tr>
<tr><td>Structure</td><td>Answer engineering produced consistent headings, tables, and sections.</td></tr>
<tr><td>Tone and Style</td><td>The final content used a professional, balanced, college-level engineering tone.</td></tr>
</table>

<h2>Ethical Considerations</h2>

<ul>
<li><strong>Human Oversight:</strong> AI-generated robotics content must not replace qualified engineering judgment or authorized maintenance decisions.</li>
<li><strong>Safety:</strong> Prompts should not instruct unqualified users to interfere with energized, moving, or safety-critical robotic equipment.</li>
<li><strong>Accuracy:</strong> Equipment limits, fault causes, performance claims, and maintenance recommendations must be verified against reliable engineering sources.</li>
<li><strong>Transparency:</strong> AI-assisted reports should disclose AI involvement when the content is used for formal engineering communication.</li>
<li><strong>Data Privacy:</strong> Proprietary machine logs, production information, maintenance records, and company data should be protected.</li>
<li><strong>Bias and Hallucination:</strong> AI may produce plausible but incorrect explanations; therefore technical outputs require verification.</li>
<li><strong>Traceability:</strong> Prompt versions, inputs, generated outputs, revisions, and approval decisions should be documented.</li>
</ul>

<h2>Final Presentation – Outline</h2>

<ol>
<li><strong>Title Slide</strong> – RoboAssist: Prompt Engineering for Robotic Maintenance Documentation</li>
<li><strong>Problem Statement</strong> – Maintenance documentation and engineering communication challenges</li>
<li><strong>Engineering Domain &amp; Project Overview</strong> – Robotics / RoboAssist concept</li>
<li><strong>Prompt Patterns Demonstrated</strong> – Query Decomposition, Decision Making, Answer Engineering, Fact Check List, Tail Generation, Menu Actions, Semantic Filter</li>
<li><strong>Case Study</strong> – Basic to final prompt progression</li>
<li><strong>Technical Article</strong> – Basic to final prompt progression</li>
<li><strong>AI Output Evaluation</strong> – Scoring and comparison</li>
<li><strong>Ethical Considerations</strong> – Safety, accuracy, privacy, and human oversight</li>
<li><strong>Final Prompt</strong> – Demonstration of the complete prompt</li>
<li><strong>Live Demonstration</strong> – Run one prompt iteration from basic to refined output</li>
<li><strong>Result &amp; Key Findings</strong></li>
<li><strong>Conclusion</strong></li>
</ol>

<h2>Prompt Repository</h2>

<table>
<tr><th>Prompt ID</th><th>Purpose</th></tr>
<tr><td>P01</td><td>Basic robotics case-study generation</td></tr>
<tr><td>P02</td><td>Query decomposition and fact-list generation</td></tr>
<tr><td>P03</td><td>Decision-making prompt for narrative selection</td></tr>
<tr><td>P04</td><td>Answer-engineering prompt for structured output</td></tr>
<tr><td>P05</td><td>Fact-check prompt for engineering claims</td></tr>
<tr><td>P06</td><td>Tail-generation prompt for lessons learned and future roadmap</td></tr>
<tr><td>P07</td><td>Menu-action prompt for article angle selection</td></tr>
<tr><td>P08</td><td>Semantic-filter prompt for tone and readability</td></tr>
<tr><td>P09</td><td>Final integrated RoboAssist prompt</td></tr>
</table>

<h2>Deliverables</h2>

<ol>
<li><strong>Complete Project Report</strong> – Problem statement, project overview, prompt patterns, iterations, evaluation, and ethics.</li>
<li><strong>Prompt Repository</strong> – Basic, refined, advanced, and final prompts used during the experiment.</li>
<li><strong>Final Presentation</strong> – Slides covering the project, prompting techniques, evaluation, and conclusion.</li>
<li><strong>Demonstration</strong> – Live or recorded walkthrough showing prompt refinement and comparison of outputs.</li>
</ol>

<h2>Result</h2>
<p>
The capstone mini project was successfully completed by applying multiple prompt patterns to a real-world robotics
engineering scenario. The RoboAssist concept was used to generate and refine a maintenance case study and a technical
article. Progressive prompting improved the organization, engineering relevance, readability, and consistency of the
generated content. The final prompts also incorporated fact verification, safety boundaries, and human validation.
</p>

<h2>Conclusion</h2>
<p>
Thus, the experiment successfully demonstrated how prompt engineering can be applied to a real-world engineering
application in robotics. Query decomposition improved organization, decision making improved content direction,
answer engineering controlled the response structure, fact-check listing improved reliability, tail generation added
depth, menu actions helped select the best communication angle, and semantic filtering improved clarity and relevance.
</p>

<p>
The project also showed that AI-generated engineering content should be treated as decision-support and communication
assistance rather than unquestioned technical authority. Human review, source verification, safety procedures,
privacy protection, and transparent AI usage remain essential before the generated content is used in practical
engineering contexts.
</p>

