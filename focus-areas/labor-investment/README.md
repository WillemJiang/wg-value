## Labor Investment

Goal: Estimate the labor investment in open source projects.

| Name                                              | Question                                                                                                                                   |
|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [Labor investment][l1]            | What was the cost of an organization for its employees to create the counted contributions (e.g., commits, issues, and pull requests)? |
| [Project velocity][l2]                            | What is the development speed for an organization?                                                                                         |
| Commit count by organization                      | How many commits do employees of an organization create?                                                                                   |
| Issue count by organization                       | How many issues do employees of an organization create?                                                                                    |
| Pull request count by organization                | How many pull requests do employees of an organization create?                                                                             |
| COCOMO by organization                            | What is value contributed by employees of an organization as measured by COCOMO?                                                           |
| Labor cost by organization                        | What was the cost of an organization for its employees to create the counted commits, issues, and pull requests (and other contributions)? |
| Labor investment by commits by organization       | How much value in commits was contributed by an organization?                                                                              |
| Labor investment by issue by organization         | How much value in issues was contributed by an organization?                                                                               |
| Labor investment by pull requests by organization | How much value in pull requests was contributed by an organization?                                                                        |

[l1]: https://github.com/chaoss/wg-value/blob/master/focus-areas/labor-investment/labor_investment.md
[l2]: https://github.com/chaoss/wg-value/blob/master/focus-areas/labor-investment/project_velocity.md

Comments / Discussion:

- Codebase cost / code counting
- Complexity measures
- Potentially find an average time required for commit/issue/pull request and then apply an assumption of how much that is worth.
- Implementation note: Issues and pull requests are not stored in a repository and will have to be calculated from a collaboration platform like GitHub or other issue trackers.
