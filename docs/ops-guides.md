# Moving a team off Claude Cowork: the open-source setup an ops team owns

This repository, `Kortix-seo/open-source-claude-cowork-ops`, holds the operations notes for a team moving off Claude Cowork onto Kortix, the open-source AI Operating System. Who approves a run, where its record lives, and what the first morning looks like belong to whoever owns the rollout.

## Who approves, written down

Inside Claude the approval step is a message-box setting, and the plan sets where it starts. The page on [Claude Cowork for teams](https://opensourceclaudecowork.com/claude-cowork-for-teams) works through who approves, who can read the record and where the work runs. On Kortix that decision comes back as a file. Approval gates you set. Off until you set them. An ops owner writes allow, ask or block per connector action, then approves the diff that carries the rule.

## Where the record lives

Session work reaches main through a change request. Merge is default-deny for agents, and the branch, the diff and the approval sit in the repo the team owns.

## The first morning

Connect the repo, set what the work may reach, choose the approval mode, run one real task, then stop at the change request. The [how-to-use walk-through](https://opensourceclaudecowork.com/how-to-use-claude-cowork) walks those steps in Claude's apps, then shows the same choices as an agent's permission block, so an ops owner sees which carry over and which become files.

The rest of this repository is the ops reference behind them: permissions, secrets and connector scope, the audit trail, and the questions teams ask first.
