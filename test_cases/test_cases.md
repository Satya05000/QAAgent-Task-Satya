1. Create Interview – Success Flow with Enhanced JD
Steps:

Navigate to "Create Interview".

Select "Enhanced JD".

Fill in title and requirements.

Click "Generate" – system populates JD.

Edit JD and click "Save".

Confirm skill extraction and review suggested skills.

Set difficulty, company name, and review suggested questions.

Set preferred answers, select AI avatar, and click "Create".

System generates public interview link.

Expected Result:
All fields save correctly, AI-generated content loads, and interview link is shown. No validation or render issues.

2. Create Interview – Manual JD Entry with Skill Editing
Steps:

Navigate to "Create Interview".

Manually enter job description.

Click "Save".

System extracts skills.

Add/remove custom skills.

Select difficulty, enter company name, and finalize setup.

Expected Result:
Manual JD is accepted, skills update dynamically, interview created successfully.

3. Create Interview – Missing Required Fields
Steps:

Leave job description blank.

Try to click "Save" or "Create".

Expected Result:
Form validation prevents proceeding. User sees clear errors: "Job description is required", etc.

4. Enhanced JD – AI Fail or Timeout
Steps:

Choose "Enhanced JD".

Provide details.

Simulate AI timeout or failure.

Expected Result:
User sees error: "We couldn’t generate a job description. Please try again later." Retry option is visible.

5. Skill Suggestions – Manual vs AI Mismatch
Steps:

Provide a niche JD with rare skills.

Observe suggested skills.

Expected Result:
System shows fallback suggestions. User can add missing skills manually. No UI break.

6. Question Editing – Custom Question Flow
Steps:

Navigate to suggested questions.

Delete existing questions.

Add a custom question.

Set preferred answer and reorder.

Expected Result:
Custom question is retained, saved correctly, reordering works with drag-and-drop or arrows.

7. Candidate Interview Link – Invalid or Expired
Steps:

Visit expired/invalid interview link.

Expected Result:
User sees friendly error: "This interview link has expired or is no longer valid."

8. Candidate – OTP Email Verification Flow
Steps:

Enter valid email.

Receive OTP.

Enter incorrect OTP.

Expected Result:
System blocks progress, error: "Invalid OTP. Please try again." Retry option appears.

9. Candidate – Resume Upload and Threshold Check
Steps:

Upload resume with low relevance.

Thresholding enabled.

Expected Result:
System gracefully informs: "Thanks for applying. This role may not be the right fit based on your profile."

10. Video Interview – Recording Flow
Steps:

Candidate clicks "Start Interview".

Camera permission denied or unavailable.

Expected Result:
Error message: "Please allow camera access to begin recording." Retry or troubleshooting instructions shown.

11. Recruiter – Response Dashboard Rendering
Steps:

Go to "Responses".

View candidate responses with video, answers, and scores.

Expected Result:
No layout overflow, videos load with fallback, responses scroll smoothly, tooltips or icons appear for scores.

12. Interview Screenings – Score Breakdown Accuracy
Steps:

View screening for a completed interview.

Observe skill scoring, communication rating, and AI summary.

Expected Result:
All metrics shown, expandable sections load correctly, edge cases like "0 score" or "no resume" handled.

13. Batch Resume Upload – AI Parsing Flow
Steps:

Recruiter uploads multiple resumes.

Trigger semantic analysis.

Expected Result:
Each resume is parsed; results shown in a sortable table. Fallback if file is corrupted or unreadable.