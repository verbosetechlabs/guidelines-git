Commit message format:
```bash
<type>: <short-description>
<optional-body>
```
1.  `type` of commit:
	- Core:
	   -   `new`: The new feature you're adding
	   -   `fix`: A bug fix
	   -   `improve`: Improvements made in the code base
	   -   `chore`: Everything else
     - Client:
	   -  cust: Represents customizations for client. Prefix the types from `Core` with `cust`. For example `cust feat`, `cust fix` etc.
  2. `short-description`: Write a short desciption in 40-50 characters. 
		- Use the imperative mood in the subject line `Fix bug` and not ~~`Fixed bug`~~
or ~~`Fixes bug`~~ or ~~`Fixing bug`~~. Imperative mood just means “spoken or written as if giving a command or instruction”.
        - Begin all subject lines with a capital letter. For example `fix: Push notification`
		- Try not to use unnecessary verb here since we have already mentioned above the `type` of our commit.
		- Do not mention file name
		- Write a concise message
3. `optional-body`: If `short-description` is not enough for describing the change. Write a body for your commit message. Separate subject from body with a blank line. Use the body to explain what and why vs. how
