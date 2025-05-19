1. Go to [https://render.com](https://render.com)
2. Create a new **Web Service**
3. Choose your GitHub repo
4. Set build command: `uvicorn main:app --host 0.0.0.0 --port 8000`
5. Set root directory: `backend/`
6. Set environment variable `MONGODB_URI`
7. Deploy
