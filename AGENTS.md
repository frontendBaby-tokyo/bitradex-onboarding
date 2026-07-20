# Repository instructions

## Markdown rendering

- Japanese documentation must not use Markdown strong-emphasis markers (`**text**`). Depending on the renderer, markers adjacent to Japanese characters or punctuation can appear as literal `**`.
- Use HTML `<strong>...</strong>` for bold text in Japanese prose and UI labels.
- Example: write `<strong>「現物」</strong>をタップする`.
- Do not add unnatural spaces around emphasis markers as a workaround.
- After editing Markdown, run the following check from the repository root. It must return no matches:

  ```sh
  rg -n '\*\*' docs --glob '*.md'
  ```

- The GitHub Actions Markdown rendering check enforces the same rule for every push and pull request.

