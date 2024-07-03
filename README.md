
## Setup Instructions

### Prerequisites
- PHP >= 8.0
- Composer
- MySQL
- Node.js (for Laravel Mix)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mukulviru/Assessment.git
   cd Assessment
   ```

2. **Install dependencies**
   ```bash
   composer install
   npm install
   npm run build
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your database credentials and other necessary configurations.

4. **Generate application key**
   ```bash
   php artisan key:generate
   ```

5. **Run database migrations**
   ```bash
   php artisan migrate
   ```

6. **Serve the application**
   ```bash
   php artisan serve
   ```
   The application will be available at `http://localhost:8000`.
