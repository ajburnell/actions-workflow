```bash
gh auth status


gh workflow list

gh run list

gh run view 5938454583

gh run view 5938454583 --log

gh run view 5938454583 --log | grep error

# gh workflow list is relative to the current repo you're in.
git remote -v

# Avoid the above by specifying
gh workflow list --repo <specify repo>

# Useful web links
# https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2204-Readme.md
# https://github.com/actions/runner-images/blob/main/images/ubuntu/toolsets/toolset-2204.json
# https://github.com/marketplace/actions/setup-go-environment
# https://github.com/marketplace