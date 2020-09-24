# 
choco install hugo -confirm

choco install hugo-extended -confirm

hugo new site ./doc

cd doc

hugo new about.md

hugo --destination="./docs"