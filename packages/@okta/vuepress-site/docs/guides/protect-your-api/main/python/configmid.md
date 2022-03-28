1. Create a new file called `.okta.env` in your project root that contains the following:

```bash
ORG_URL=https://${yourOktaDomain}
```

2. Replace the placeholder with your own value that you obtained earlier.

3. Add the following into your app file:

```python
load_dotenv('.okta.env')
```