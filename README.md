# Cooking Menu

## TODO

- [ ] Make it Deploy (on Vercel)
- [ ] Scaffold basic UI with mock data
  - [ ] Home Page ( Unprotected )
    - API:
      - GET: `/api/menu/?phone=8447824248&day=Monday`
  - [ ] Sign up page ( unprotected )
    - API:
      - POST: `/api/create-user`
  - [ ] Login page ( unprotected )
    - API:
      - POST: `/api/login`
  - [ ] Forgot Password Page ( protected )
    - API:
      - PUT: `/api/update-password`
  - [ ] Create your menu for this week page ( protected )
    - API:
      - GET: `/api/admin-menu/1`
      - POST: `/api/create-admin-menu/1`
      - PUT: `/api/update-admin-menu/1`
- [ ] Actually setup a database
- [ ] Attach database to UI
- [ ] Add Authentication (w/ Clerk)
- [ ] Error Management (w/ Sentry)
- [ ] Add Analytics (w/ Google Analytics or posthog)
- [ ] Rate Limit (w/ Upstash)
