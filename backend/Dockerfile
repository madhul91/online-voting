# 1. Base image
FROM node:18-alpine

# 2. Working directory
WORKDIR /backend

# 3. Copy package files
COPY package*.json ./

# 4. Install dependencies
RUN npm install --production

# 5. Copy source code
COPY . .

# 6. Expose backend port
EXPOSE 8001

# 7. Start server
CMD ["npm","start"]
