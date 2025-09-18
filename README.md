# guestbook

ghcr for: https://github.com/adamplansky/kargo-simple


GITHUB_PAT=$(op item get "PAT kargo-example"  --field token --reveal)
echo $GITHUB_PAT


echo "$GITHUB_PAT" | docker login ghcr.io -u adamplansky --password-stdin

# ghcr
https://github.com/adamplansky?tab=packages
https://github.com/users/adamplansky/packages/container/package/guestbook
