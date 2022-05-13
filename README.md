mkdir -p hooks
git config core.hooksPath hooks

git config -l --local

cd hooks/
vi pre-commit
chmod +x ./hooks/pre-commit
