# CegidPulseClient

**CegidPulseClient** is a reusable .NET class library built using the Clean Architecture pattern. It provides an abstraction layer and communication methods for integrating with the **Cegid Pulse AI API**.

---

## 📌 Purpose

This library is designed to:
- Provide a clean and testable interface for working with Cegid Pulse.
- Encapsulate all HTTP/API logic and domain models related to Cegid Pulse.
- Be easily integrated into other .NET applications such as chatbots, services, or backoffice tools.

---

## 📁 Project Structure (Clean Architecture)

The library follows Clean Architecture principles and is divided into the following layers:

- **Domain**:
  - Contains core entities, enums, and interfaces that define the domain logic.
- **Application**:
  - Contains use cases (business logic), DTOs, and interfaces for services.
- **Infrastructure**:
  - Implements integrations with Cegid Pulse (HTTP clients, authentication, etc).
- **Presentation** *(optional)*:
  - Provides a minimal CLI or API layer for demo/testing purposes.

---

## 🚀 Getting Started

### Prerequisites
- .NET 7 or newer
- Visual Studio or any compatible IDE

### Installation
Clone the repository and build the solution:

```bash
git clone https://your-repo-url/cegid-pulse-client.git
cd cegid-pulse-client
dotnet build
