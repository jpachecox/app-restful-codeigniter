# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
and this project adheres to [Semantic Versioning](https://semver.org/).

---

## [Unreleased]

### Added

- Base project structure (Domain, Infrastructure, Services, DTOs)
- Initial PSR-4 autoload configuration
- Base `.env` configuration
- Initial Composer setup
- Initial project setup with CodeIgniter 4.7.2
- Development environment configuration
- Created project structure:
  - `app/Domain/Entities`
  - `app/Domain/Repositories`
  - `app/Infrastructure/Repositories`
  - `app/Services`
  - `app/DTOs`
  - `app/Validators`
  - `app/Traits`
- Added `.gitignore`
- Initialized Git repository
- Base logging configuration (`writable/logs`)
- PSR-4 autoload validation
- Database configuration in `.env`

---

## Notes

- The project is currently in its initial setup phase
- Next steps:
  - Implement JWT authentication
  - Create versioned endpoints (`/API/V1`)
  - Integrate structured validation
  - Add API documentation (Swagger/OpenAPI)

---

## Change Types

- **Added** → for new features  
- **Changed** → for changes in existing functionality  
- **Deprecated** → for soon-to-be removed features  
- **Removed** → for removed features  
- **Fixed** → for bug fixes  
- **Security** → for vulnerability fixes
