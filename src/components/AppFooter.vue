<script lang="ts" setup></script>

<template>
  <footer>
    <div class="container">
      <p>&copy; 2023 - Nadun Adithya.Developed with Vue3</p>
      <div class="social-links">
        <a
          class="social-link"
          href="https://www.linkedin.com/in/mathis-dousse"
          target="_blank"
          aria-label="link to my linkedin"
        >
          <svg viewBox="0 0 50 50" width="20" height="20" fill="currentColor">
            <path
              d="M41,4H9C6.24,4,4,6.24,4,9v32c0,2.76,2.24,5,5,5h32c2.76,0,5-2.24,5-5V9C46,6.24,43.76,4,41,4z M17,20v19h-6V20H17z M11,14.47c0-1.4,1.2-2.47,3-2.47s2.93,1.07,3,2.47c0,1.4-1.12,2.53-3,2.53C12.2,17,11,15.87,11,14.47z M39,39h-6c0,0,0-9.26,0-10 c0-2-1-4-3.5-4.04h-0.08C27,24.96,26,27.02,26,29c0,0.91,0,10,0,10h-6V20h6v2.56c0,0,1.93-2.56,5.81-2.56 c3.97,0,7.19,2.73,7.19,8.26V39z"
            ></path>
          </svg>
        </a>
        <a
          class="social-link"
          href="https://github.com/FeckNeck"
          target="_blank"
          aria-label="link to my github"
        >
          <svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor">
            <path
              d="M 10.898438 2.101562 C 6.300781 2.601562 2.601562
            6.300781 2.101562 10.800781 C 1.601562 15.5 4.300781 19.699219
            8.398438 21.300781 C 8.699219 21.398438 9 21.199219 9 20.800781 L 9
            19.199219 C 9 19.199219 8.601562 19.300781 8.101562 19.300781 C
            6.699219 19.300781 6.101562 18.101562 6 17.398438 C 5.898438 17
            5.699219 16.699219 5.398438 16.398438 C 5.101562 16.300781 5
            16.300781 5 16.199219 C 5 16 5.300781 16 5.398438 16 C 6 16 6.5
            16.699219 6.699219 17 C 7.199219 17.800781 7.800781 18 8.101562 18 C
            8.5 18 8.800781 17.898438 9 17.800781 C 9.101562 17.101562 9.398438
            16.398438 10 16 C 7.699219 15.5 6 14.199219 6 12 C 6 10.898438 6.5
            9.800781 7.199219 9 C 7.101562 8.800781 7 8.300781 7 7.601562 C 7
            7.199219 7 6.601562 7.300781 6 C 7.300781 6 8.699219 6 10.101562
            7.300781 C 10.601562 7.101562 11.300781 7 12 7 C 12.699219 7
            13.398438 7.101562 14 7.300781 C 15.300781 6 16.800781 6 16.800781 6
            C 17 6.601562 17 7.199219 17 7.601562 C 17 8.398438 16.898438
            8.800781 16.800781 9 C 17.5 9.800781 18 10.800781 18 12 C 18
            14.199219 16.300781 15.5 14 16 C 14.601562 16.5 15 17.398438 15
            18.300781 L 15 20.898438 C 15 21.199219 15.300781 21.5 15.699219
            21.398438 C 19.398438 19.898438 22 16.300781 22 12.101562 C 22
            6.101562 16.898438 1.398438 10.898438 2.101562 Z M 10.898438
            2.101562 "
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
footer {
  background-color: var(--footer);
  color: white;
}

footer > div {
  align-items: center;
  display: flex;
  justify-content: space-between;
  padding-block: 2rem;
}

.social-links {
  align-items: center;
  display: flex;
  flex-direction: row;
  gap: 1rem;
}

.social-link {
  transition: color 300ms ease;
}

.social-link:hover {
  color: var(--teal);
}

@media (max-width: 768px) {
  footer > div {
    flex-direction: column;
    gap: 1rem;
  }
}
</style>
