FROM node:14

WORKDIR /usr/src/frontend

COPY package*.json ./
RUN npm install

COPY . .

# Expose the port on which your Svelte app runs (e.g., 5000)
EXPOSE 8080

# Run the Svelte development server
CMD ["npm", "run", "dev"]