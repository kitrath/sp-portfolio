# Single Page Portfolio

## User Story
**AS AN** employer looking for candidates with experience building single-page applications<br>
**I WANT** to view a potential employee's deployed React portfolio of work samples<br>
**SO THAT** I can assess whether they're a good candidate for an open position

## Acceptance Criteria
**GIVEN** a single-page application portfolio for a web developer
- **WHEN** I load the portfolio<br>
**THEN** I am presented with a page containing a header, a section for content, and a footer
- **WHEN** I view the header<br>
**THEN** I am presented with the developer's name and navigation with titles corresponding to different sections of the portfolio
- **WHEN** I view the navigation titles<br>
**THEN** I am presented with titles About Me, Portfolio, Contact, and Resume, and the title corresponding to the current section is highlighted
- **WHEN** I load the portfolio for the first time<br>
**THEN** the About Me title and section are selected by default
- **WHEN** I am presented with the About Me section<br>
**THEN** I see a recent photo or avatar of the developer and short bio about them
- **WHEN** I am presented with the portfolio section<br>
**THEN** I see titled images of six of the developer's applications with links to both the deplloyed applications and the corresponding GitHub repository
- **WHEN** I am presented with the Contact section<br>
**THEN** I see a contact form with fields for a name, an email address, and a message
- **WHEN** I move my cursor out of one of the form fields without entering text<br>
**THEN** I receive a notification that this field is required
- **WHEN** I enter text into the email address field<br>
**THEN** I receive a notification if I have entered an invalid email address
- **WHEN** I am presented with the Resume section<br>
**THEN** I see a link to a downloadable resume and a list of the developer's proficiencies
- **WHEN** I view the footer<br>
**THEN** I am presented with text or icon links to the developer's GitHub and LinkedIn profiles, and their profile on a third platform (Stack Overflow, Twitter)