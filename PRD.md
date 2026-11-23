                PRODUCT REQUIREMENTS DOCUMENT
                     TutoringPro
                The right lecturer for the way you learn

    How to Read This Document
        Statements marked [Confirmed] come from the product idea as defined by the team. Statements marked [Assumption] are the team's best current guesses and were validated through observations due to time constraint.
            Table of Contents
            •	1. Product Overview
            •	2. Problem Statement
            •	3. Business Model and Objectives
            •	4. Research Plan and Findings
            •	5. Target Users
            •	6. Stakeholders
            •	7. Proposed Solution: How Matching Works
            •	8. User Stories and Acceptance Criteria
            •	9. Functional Requirements
            •	10. Non-Functional Requirements
            •	11. Scope and Priorities (MoSCoW) and MVP Definition
            •	12. Business Rules
            •	13. Assumptions, Risks and Open Questions

 1. Product Overview
        TutoringPro is a web-based platform that matches students with the tutors best suited to help them. Both sides complete a short survey. Students describe what they need help with and how they learn best. Tutors describe what they teach, how they teach and when they are available. The system compares the two sets of answers and shows each student a ranked list of suitable tutors, with a reason for each match. Matched students can then book a paid tutoring or consultation session, and the platform takes a commission on each paid session.
        One-line pitch: The university decides who teaches your class. TutoringPro helps you find who you learn best from.

 2. Problem Statement
        2.1 The problem
            Students are assigned lecturers randomly. A lecturer's subject knowledge may be excellent, but their teaching style, pace and approach may not suit a particular student. A student who is struggling has no structured way to find a lecturer, within or outside their own class, whose style and expertise fit their needs. Lecturers likewise have no way to reach students who would benefit most from their approach.
        2.2 Who has the problem
            •	Students who struggle in a course because of a mismatch with the lecturer's teaching style, not because of ability.
            •	Students who want extra help and do not know which lecturer to approach.
            •	Lecturers who would like to offer tutoring or mentoring but have no channel to be discovered by the right students.
        2.3 How people cope today
            [Assumption, to be validated in Section 4]
                Coping method	                                    Weakness
                Asking course mates which lecturer is “good”	    Opinions are informal, biased and not matched to the individual.
                WhatsApp course groups	                            Information is scattered and unstructured, and gives no way to find tutors.
                Hiring private tutors found through word of mouth	No quality signal, no accountability, no link to the university's own lecturers.
        2.4 Why existing solutions fall short
            •	General tutoring marketplaces are not built around a specific university's lecturers and course codes.
            •	Lecturer rating sites rate popularity, not fit. A lecturer who suits one learner may not suit another.
            •	Nothing combines both sides' preferences (student and lecturer) in a structured match.
        
 3. Business Model and Objectives
        3.1 Business model
            Participant                                     	Description
            Students	                                        Complete a survey describing courses, learning preferences, needs and constraints.
            Lecturers/Tutors	                                Complete a survey describing subjects, teaching style, availability, rates and a                                                    a short exam to ensure actual knowledge of the course/subject
            TutoringPro platform	                            Provides surveys, matching, booking, payments, moderation and exam for tutor  verification
            Revenue	                                            The platform earns a commission on each paid session.
            [Confirmed] The platform offers a paid tutoring service and takes a commission on each paid session.
            [Open] Commission rate, who pays it (student, lecturer or both) and how payouts work are not yet decided.
            [Assumption] A person is a user first. “Student” and “lecturer” are roles, not separate products.
        
        3.2 Business objectives
            ID	    Objective
            BO-1	Help students find lecturers whose teaching style and expertise fit them.
            BO-2	Create a revenue stream through commission on paid tutoring sessions.
            BO-3	Attract enough lecturers to give students real choice in each course.
            BO-4	Build trust: verified lecturers, verified students and transparent reporting.
            BO-5	Improve match quality over time using feedback after sessions.

 4. Research Plan and Findings
    
        4.1 Research objectives
            •	Confirm that students experience a mismatch with randomly assigned lecturers.
            •	Learn how students currently look for extra academic help.
            •	Learn whether lecturers are willing to offer paid tutoring, and under what conditions.
            •	Learn what students are willing to pay.
        4.2 Method
            Unfortunately, due to time constraint our findings were based on observation of happenings in the school university learning sector


5. Target Users
        5.1 Student (primary user)
            •	Who: Undergraduate students at Babcock University.
            •	Goal: Find a lecturer/tutor who helps them understand a course and improve their grades.
            •	Struggles: No say in lecturer assignment. Unsure whom to ask. Worried about quality and cost.
            •	Typical device: [Assumption] Mostly smartphone, sometimes laptop, on campus Wi-Fi or mobile data.
        5.2 Lecturer (provider)
            •	Who: Lecturers, and possibly students, who want to offer tutoring or consultation.
            •	Goal: Be discovered by students who benefit from their style, and earn additional income.
            •	Struggles: Limited time, wanting to avoid unsuitable or overwhelming requests, and wanting protection from conflicts of interest.
        5.3 Administrator
            •	Who: Platform operators (and possibly a university representative).
            •	Goal: Keep the platform safe, verify lecturers, handle reports and monitor payments.
        A user can hold more than one role (for example, student who is also a tutor). Roles are attributes of a user account, not separate account types.


6. Stakeholders
        Stakeholder	                        Interest	                                                Possible tension
        Founder / product team	            Growth, revenue, product success	                        Wants speed; others want safeguards
        Students	                        Finding the right lecturer at an affordable price	        Want low cost; lecturers want fair pay
        Lecturers	                        Fair earnings, control over time, protection of reputation	May not want students rating or ranking them publicly
        University management / registry	Academic integrity, policy compliance, reputation	        May restrict paid tutoring by staff
        Customer support	                Handling complaints and disputes	                        Needs clear rules and admin tools
        Payment provider (external)	        Transaction processing	                                    Fees and availability affect pricing



7. Proposed Solution: How Matching Works
        8.1 Flow
            •	Student and lecturer each register and verify their identity.
            •	Each completes a role-specific survey (the “profile survey”).
            •   Response from profile survey is save under user profile and can be viewed by both parties.
            •	The system filters out lecturers who do not meet the student's hard requirements.
            •	The system scores the remaining lecturers and ranks them.
            •	The student sees the top matches with a match percentage and the reasons.
            •	The student sends a session request. The lecturer accepts or declines.
            •	After the session, both sides give feedback, which is used to improve matching.

        8.2 Survey dimensions
        Dimension	                Student answers	                            Lecturer answers	                    Used as
        Course or topic	            Courses where help is needed	            Courses and topics they can teach	    Hard filter
        Availability	            Preferred days and times	                Days and times offered	                Hard filter
        Session mode	            Physical, online or either	                Physical, online or either	            Hard filter
        Budget and rate	            Maximum price per hour	                    Price per hour	                        Hard filter
        Learning or teaching style	Theory-first, example-first,                Same options                            Weighted score
                                    practice-first, discussion, visual		
        Pace	                    Slow, moderate, fast	                    Same options	                        Weighted score
        Communication preference	Formal, relaxed, encouraging, challenging	Same options	                        Weighted score
        Language	                Preferred languages	                        Languages used	                        Weighted score
        Goal	                    Pass, improve grade, deeper understanding,  Types of help offered                   Weighted score
                                    project help		

        8.2.1 Matching approach (conceptual, technology-independent)
        Step 1: Hard filters. A lecturer who fails any hard filter is not shown.
        Step 2: Weighted similarity score. For each style dimension, compute how closely the student's preference matches the lecturer's. Combine them with weights. match_score = Σ (weight_i × similarity_i), expressed as a percentage.
        Step 3: Explanation. The system lists the top two or three contributing dimensions in plain language (for example, “You prefer example-first learning, and this lecturer teaches with worked examples”).
        Step 4: Refinement. Initial weights are set by the team. They are later adjusted using session feedback.


8. User Stories and Acceptance Criteria
        US-01: Register and verify
        As a student, I want to create an account with my university email so that only genuine Babcock students use the platform.
            Acceptance criteria
                •	Registration requires a valid university email address in the agreed format.
                •	The email must be verified (for example, by a link) before the account is active.
                •	A duplicate email is rejected with a clear error.
                •	Passwords are stored only in hashed form.
        US-02: Lecturer registration and approval
            As a lecturer, I want to register and have my staff status confirmed so that students trust that I am real.
            Acceptance criteria
                •	A lecturer account is created in a “pending” state.
                •	An administrator can approve or reject a pending lecturer based on the filters.
                •	A pending lecturer cannot appear in match results.
                •	A rejected lecturer receives a notification with a reason.
        US-03: Student survey
                As a student, I want to answer a short survey about how I learn so that the app can match me to suitable lecturers.
                Acceptance criteria
                •	The survey includes all hard-filter and style dimensions in Section 8.2.
                •	Required questions must be answered before submission.
                •	A student can edit and resubmit answers, and the latest answers are used.
                •	The survey can be completed in under 5 minutes.
        US-04: Lecturer survey and profile
                As a lecturer, I want to describe my teaching style, subjects, rate and availability so that the right students find me.
                Acceptance criteria
                •	Lecturer sets courses, style, pace, mode, rate and weekly availability.
                •	Price must be a valid amount greater than zero.
                •	Lecturer can pause their listing without deleting their profile.
                •	Changes take effect for new matches immediately.
        US-05: See matches
                As a student, I want to see a ranked list of lecturers with reasons so that I can choose confidently.
                Acceptance criteria
                •	Only authenticated students with a completed survey can request matches.
                •	Results exclude lecturers who fail any hard filter.
                •	Each result shows match percentage, key reasons, rate and availability summary.
                •	If no lecturer matches, the student sees a clear message and suggestions to relax filters.
                •	Results are ordered from highest to lowest score.
        US-06: Request a session
                As a student, I want to send a session request to a lecturer so that we can arrange tutoring.
                Acceptance criteria
                •	The request includes course, preferred time and a short message.
                •	The system blocks requests that break a business rule (for example, conflict of interest in Section 13).
                •	Duplicate pending requests to the same lecturer for the same slot are rejected.
                •	The lecturer is notified of the request.
        US-07: Accept or decline
            As a lecturer, I want to accept or decline requests so that I control my schedule.
            Acceptance criteria
            •	Only the addressed lecturer can respond.
            •	Accepting a request creates a confirmed session and marks that time slot as unavailable.
            •	Declining requires no reason but allows an optional one.
            •	A request unanswered after the agreed period expires automatically.



9. Functional Requirements
        ID	    Requirement	                                                                                            Priority
        FR-01	Users can register with a university email and log in.	                                                Must
        FR-02	The system verifies email ownership before activating an account.	                                    Must
        FR-03	Users have a role (student, lecturer, administrator); a user may hold more than one.	                Must
        FR-04	Administrators can approve or reject lecturer accounts.	                                                Must
        FR-05	Students can complete and edit a learning-preference survey.	                                        Must
        FR-06	Lecturers can complete and edit a teaching-profile survey, including courses, rate and availability.	Must
        FR-07	Lecturers must pass a subject exam before approval	                                                    Must
        FR-08	The system applies hard filters (course, availability, mode, budget) to produce eligible lecturers.	    Must
        FR-09	The system computes a weighted match score for eligible lecturers.	                                    Must
        FR-10	Students can view ranked matches with score and reasons.	                                            Must
        FR-11	Students can send session requests to matched lecturers.	                                            Must
        FR-12	Lecturers can accept or decline requests; accepted requests become sessions.	                        Must
        FR-13	The system enforces conflict-of-interest rules (Section 13).	                                        Must
        FR-14	Users receive notifications for requests, responses and session reminders.	                            Should
        FR-15	Students can pay for a confirmed session in the app.	                                                Should
        FR-16	The system calculates and records platform commission per payment.	                                    Should
        FR-17	Students can submit post-session feedback.	                                                            Should
        FR-18	Users can report accounts or sessions.	                                                                Should
        FR-19	Administrators can review reports and suspend accounts.	                                                Should
        FR-20	Lecturers can view earnings and payout status.	                                                        Could
        FR-21	Students can save favourite lecturers.	                                                                Could
        FR-22	Match weights are adjusted using aggregated feedback.	                                                Could

10. Non-Functional Requirements
        ID	    Category	    Requirement (measurable target)
        NFR-01	Performance	    95% of match requests return results within 3 seconds under normal load (target of 200 concurrent users; to be confirmed).
        NFR-02	Security	    Passwords are never stored in plain text; they are hashed.
        NFR-03	Security	    Role-based access: students cannot access lecturer-only or administrator functions.
        NFR-04	Privacy	        Student survey answers and contact details are visible to users that have access to the other user profile.
        NFR-05	Privacy	        Student data handling with utmost care and security.
        NFR-06	Reliability	    No paid session without a payment record and vice versa.
        NFR-07	Scalability	    The system can grow to the full university population (several thousand students) without much redesign.
        NFR-08	Usability	    A new student can complete registration and the survey in under 10 minutes without help.
        NFR-09	Explainability	Every match result must show at least two reasons for matching.

11. Scope and Priorities (MoSCoW) and MVP Definition
        12.1 MoSCoW
        Priority	    Features
        Must have	    Registration and email verification; roles for users; lecturer approval; student survey; lecturer survey and profile; hard filters; weighted matching; ranked results with reasons; session request; accept or decline; conflict-of-interest rule.
        Should have	    Notifications; in-app payment with commission; post-session feedback; reporting; administrator moderation.
        Could have	    Lecturer earnings dashboard; favourite lecturers; automatic weight refinement from feedback; calendar sync.
        Won't have(this
        version)       Video call hosting; group sessions; mobile native apps; integration with the university's official timetable or grading systems; multi-university support.

        12.2 MVP definition
        The MVP is the smallest complete product that proves one thing: that survey-based matching leads students and lecturers to book sessions with each other.
        MVP includes:
        •	Register, verify and log in (students, lecturers, administrators).
        •	Admin approval of lecturers.
        •	Student and lecturer surveys.
        •	Matching with hard filters and weighted scoring.
        •	Ranked match results with reasons.
        •	Session request, accept and decline.
        •	Conflict-of-interest protection.
        •	Basic reporting and moderation.
        MVP does not include: anything under Won't Have.

12. Business Rules
        ID	    Rule	                                                                            Status
        BR-01	Only users with a verified university email can register.	                        Proposed
        BR-02	A lecturer must be approved by an administrator before appearing in matches.	    Proposed
        BR-03	Conflict of interest: a lecturer cannot be booked for paid tutoring by a student    Proposed, needs university policy confirmation
        they currently teach or assess in that course.	
        BR-04	A lecturer sets their own rate within platform limits (limits to be decided).	    Proposed
        BR-05	A session is confirmed only when the lecturer accepts.	                            Proposed
        BR-06	Platform commission applies to every paid session. Rate and who bears it are 
        to be decided.	                                                                            Confirmed (existence); rate is open
        BR-07	A suspended user cannot send or receive requests.	                                Proposed
        BR-08	Survey answers are used only for matching and platform improvement.	                Proposed
        BR-09	Matching is not grading. The platform makes no claim about grades or 
        academic outcomes.	                                                                        Proposed


13. Assumptions, Risks and Open Questions
        14.1 Assumptions (to be validated)
        ID	    Assumption	                                                                How we validate it
        A-01	Students would use a tool to find lecturers who suit their learning style.	Observation
        A-02	Students will pay for tutoring from university lecturers.	                Observation
        A-03	Lecturers are willing to offer paid tutoring through a platform.	        Observation
        A-04	Teaching and learning style are meaningful predictors of a good match.	    Session feedback after launch
        A-05	Most students use smartphones and can access the web app on campus.	        Observation
        A-06	A short survey (under 5 minutes) is enough to get usable matches.	        To be tested after launch

        14.2 Risks
        Risk	                                                Impact	                        Mitigation
        University forbids or restricts paid tutoring by staff	Business model blocked	        Ask the registry early; design a free “consultation” mode as fallback.
        Too few lecturers join	                                Poor choice, weak matches	    Start with willing lecturers in a few departments.
        Lecturers object to being “ranked”	                    Resistance	                    Show fit reasons, not public rankings; lecturer controls visibility.
        Students answer carelessly or dishonestly	            Poor match quality	            Short surveys, feedback loop.
        Payment failures or disputes	                        Trust loss, financial errors	Idempotent payments, audit log.

