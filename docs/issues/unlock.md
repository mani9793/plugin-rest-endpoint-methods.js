---
name: Unlock an issue
example: octokit.issues.unlock({ owner, repo, issue_number })
route: DELETE /repos/{owner}/{repo}/issues/{issue_number}/lock
scope: issues
type: API method
---

# Unlock an issue

Users with push access can unlock an issue's conversation.

```js
octokit.issues.unlock({
  owner,
  repo,
  issue_number,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>owner</td><td>yes</td><td>

</td></tr>
<tr><td>repo</td><td>yes</td><td>

</td></tr>
<tr><td>issue_number</td><td>yes</td><td>

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://developer.github.com/v3/issues/#unlock-an-issue).
