---
title: Shots - Rebounds
---

# Rebounds

* TOC
{:toc}

## List rebounds for a shot

    GET /shots/:id/rebounds

### Response

<%= headers 200 %>
<%= json(:rebound) { |hash| [hash] } %>
