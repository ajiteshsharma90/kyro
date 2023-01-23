 
FROM python:3.9
 
WORKDIR /cosmos-fast

RUN pip install fastapi
RUN pip install fastapi uvicorn
RUN pip install uvicorn
RUN pip install python-dotenv
RUN pip install aiohttp
RUN pip install azure-cosmos


COPY . .

EXPOSE 8000

CMD ["python", "-m", "uvicorn", "main:app", "--reload"]