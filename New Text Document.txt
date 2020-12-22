mkdir -p ~/.streamlit/
echo "[general]
email = \"rish.mish.2607@gmail.com\"
" > ~/.streamlit/credentials.toml
echo "[server]
headless = true
port = $PORT
enableCORS = false
" > ~/.streamlit/config.toml