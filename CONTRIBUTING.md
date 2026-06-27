# Contributing to Job Hunt Tracker

## How to Add Information

### 1. Adding Job Applications

- Update `applications/applications.csv` with new applications
- Include: Company Name, Position, City, Status, Resume Used, Date Applied, Follow-up Date

### 2. Adding Companies

- Add to relevant JSON file in `companies/`
- Include: Company Name, Website, Tech Stack, Company Type, City, Contact Info (if available)

### 3. Adding Resumes

- Place in `resumes/skill-based/` or `resumes/city-based/`
- Name format: `[skill]-resume.pdf` or `[city]-resume.pdf`

### 4. Adding Email Templates

- Add to `templates/cold-emails/`
- Name format: `[skill]-[city]-template.txt` or `[company-type]-template.txt`

## Naming Conventions

- Use kebab-case for file names: `senior-developer`, `surat-based`
- Use clear, descriptive names
- Include date or version if multiple versions exist

## Best Practices

- Keep sensitive information (like personal details) out of templates
- Use placeholders in templates: `[COMPANY_NAME]`, `[YOUR_NAME]`, `[POSITION]`
- Update application status regularly
- Share successful email templates with the team

## Feedback & Suggestions

- Create an Issue for bugs or feature requests
- Create a Pull Request for improvements
- Discuss major changes in Issues first
