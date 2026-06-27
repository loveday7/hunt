# How to Use Job Hunt Tracker

## Getting Started

### 1. Set Up Your Profile

- Create a folder with your name in `resumes/`
- Add your skill-based and city-based resumes
- Update your contact information in a private note (don't commit sensitive data)

### 2. Track Your Applications

**Open `applications/applications.csv` and add entries:**

| Field | Description |
|-------|-------------|
| Company Name | Full company name |
| Position | Job title you applied for |
| City | Target city |
| Company Type | Startup / Mid-size / Enterprise |
| Applied Date | When you applied (YYYY-MM-DD) |
| Status | Applied / Interview Scheduled / Rejected / Offer / Negotiating |
| Resume Used | Which resume file you submitted |
| Follow-up Date | When to follow up (YYYY-MM-DD) |
| Notes | Any important details |
| Contact Person | Hiring manager/HR email if available |

### 3. Research Companies

- Browse `companies/startups.json` and `companies/mid-size.json`
- Note important details: tech stack, hiring roles, HR email
- Add new companies you discover

### 4. Use Email Templates

1. Go to `templates/cold-emails/`
2. Choose relevant template (skill, city, or company type based)
3. Copy the template content
4. Replace all placeholders `[LIKE_THIS]` with your information
5. Personalize with specific details about the company
6. Save the email and send

### 5. Manage Resumes

- Keep resumes in `resumes/skill-based/` or `resumes/city-based/`
- Update regularly with new achievements
- Reference used resume in `applications.csv`
- Create variants for different focuses

## Tips for Success

### Application Strategy

- Track everything - even rejections help you improve
- Follow up after 1-2 weeks if no response
- Personalize each email template significantly
- Keep templates as guides, not copy-paste material

### Resume Optimization

- Use ATS-friendly format
- Include relevant keywords from job description
- Quantify achievements (percentages, numbers, time saved)
- Keep to 1-2 pages
- Update before each application cycle

### Email Best Practices

- Subject line should be clear and relevant
- Keep email concise (3-4 short paragraphs)
- Mention specific reason why you're interested in the company
- Include clear call-to-action
- Always attach resume and provide contact info
- Follow up if no response after 1 week

## Collaboration with Friends

1. **Share Opportunities** - Add interesting companies to `companies/` directory
2. **Review Templates** - Give feedback on email templates that work
3. **Track Progress** - Update `applications.csv` regularly
4. **Create Issues** - Discuss strategies and improvements via Issues
5. **Pull Requests** - Propose improvements to templates or structure

## Measuring Progress

Track these metrics:
- Applications sent per week
- Response rate (interviews / applications)
- Success rate (offers / interviews)
- Average time to first response
- Most effective companies/cities
- Best performing email templates

## Troubleshooting

**Q: Should I personalize templates?**  
A: YES! Use templates as starting point, customize heavily. Hiring managers can tell copy-paste.

**Q: How often should I follow up?**  
A: After 1 week if no response, then once more 1 week later. Don't spam.

**Q: What if I get rejected?**  
A: Note it and keep moving. Sometimes it's just fit. Review your materials and improve.

**Q: How do I track multiple applications to same company?**  
A: Add separate rows with different positions or dates. Update status as it changes.
