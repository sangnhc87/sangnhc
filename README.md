# sangnhc
# Tạo thư mục cho repo (ví dụ)
mkdir sangnhc-latex-repo
cd sangnhc-latex-repo

# Khởi tạo git (nếu chưa có)
git init

# Tạo thư mục .github/workflows
mkdir -p .github/workflows

# Tạo file build-and-deploy.yml
# Sử dụng trình soạn thảo văn bản của bạn và dán nội dung YML vào đây
# Ví dụ: nano .github/workflows/build-and-deploy.yml
touch .github/workflows/build-and-deploy.yml

# Tạo file main.tex
# Sử dụng trình soạn thảo văn bản và dán nội dung LaTeX vào đây
# Ví dụ: nano main.tex
touch main.tex

# Tạo file README.md
touch README.md

# Nếu có ảnh, ví dụ:
# touch example.png

# Sau đó, add và commit tất cả các file này
git add .
git commit -m "Initial commit for LaTeX build and deploy"

# Kết nối với remote repo trên GitHub (nếu chưa có)
# git remote add origin <URL_repo_cua_ban>

# Push lên GitHub
git push -u origin main