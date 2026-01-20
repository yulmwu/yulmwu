## Convention

```
<type>(<scope?>): <subject>

<body?>

<footer?>
```

- `<type>`: `feat` | `fix` | `docs` | `style` | `refactor` | `test` | `chore` | `perf` | `ci` | `build` | `revert` ...
- `<scope>` (Optional): modules or scopes such as `auth`, `api`, `wiki`.
- `<subject>`: use imperative sentences, avoid periods, lowercase the first letter, limit to 50 characters and english only.
- `<body>` (Optional): within 72 characters per line, focusing on "What" and "Why", and "How" explained by the source code.
- `<footer>` (Optional): issue tracking, etc.

## Examples

```
feat(order): support bulk checkout
fix(payment): handle timeout correctly
refactor(auth): extract token validation logic
docs: add architecture diagram
chore: bump node version to 20.x
```

```
feat: add rate limit to login API

- prevent brute force attacks
- limit to 5 requests per minute per IP

Closes #123
Refs #456
```
