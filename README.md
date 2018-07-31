# linked-list

## Description

- Employment networking platform connecting professionals and companies, modeled after LinkedIn and AngelList
- RESTful API created using Node.js and Express, leveraging Mongoose to model MongoDB non-relational database

## API

- Collections include Users, Companies, Jobs

### CRUD for Users

- Collection endpoint: "/users"
- Specific user endpoint: "/users/{username}"
- Create new user: POST "/users", authorization/login required
- Read all users: GET to "/users"
- Read specific user: GET to "/users/{username}"
- Update a specific user: PATCH to "/users/{username}", authorization/login required, authentication/correct user required
- Delete a specific user: DELETE to "/users/{username}", authorization/login required, authentication/correct user required

### CRUD for Companies

- Collection endpoint: "/companies"
- Specific company endpoint: "/companies/{companyHandle}"
- Create new company: POST "/companies", authorization/login required
- Read all companies: GET to "/companies"
- Read specific company: GET to "/companies/{companyHandle}"
- Update a specific company: PATCH to "/companies/{companyHandle}", authorization/login required, authentication/correct user required
- Delete a specific company: DELETE to "/companies/{companyHandle}", authorization/login required, authentication/correct user required

### CRUD for Jobs

- Collection endpoint: "/jobs"
- Specific job endpoint: "/jobs/{jobId}"
- Create new job: POST "/jobs", authorization/login required
- Read all jobs: GET to "/jobs"
- Read specific job: GET to "/jobs/{jobId}"
- Update a specific job: PATCH to "/jobs/{jobId}", authorization/login required, authentication/correct company required
- Delete a specific job: DELETE to "/jobs/{jobId}", authorization/login required, authentication/correct company required

### React/Redux frontend

- First pass at some initial pair-programmed features: [https://github.com/karlsecco/linkedlist-frontend](https://github.com/karlsecco/linkedlist-frontend)

## Instructions to run locally

```bash
git clone https://github.com/karlsecco/linked-list.git
cd linked-list
npm install
```

## Notes about the author

Karl Secco is a full stack software engineer proficient in React Native, React, Redux, and JavaScript, passionate about creating clean, maintainable code and streamlined user experiences. A graduate of [Rithm School](https://www.rithmschool.com/), Karl most recently fulfilled a React Native (iOS) contract for [Groupmuse](https://www.groupmuse.com/). For more information, please visit [www.karlsecco.com](http://www.karlsecco.com).
