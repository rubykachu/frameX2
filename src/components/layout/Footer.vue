<template>
  <footer class="bg-white border-t border-gray-200 py-4">
    <div class="container mx-auto px-4">
      <div class="flex items-center justify-between">
        <!-- Copyright -->
        <p class="text-sm text-gray-500">
          &copy; {{ copyrightYears(2025) }} FrameX2
        </p>

        <!-- Developer Info with Social -->
        <div class="flex items-center space-x-3">
          <p class="text-sm text-gray-500">
            Developed by Tăng Quốc Minh
          </p>
          <div class="flex items-center space-x-2">
            <a
              href="https://www.facebook.com/tangquocminh"
              target="_blank"
              class="text-gray-400 hover:text-blue-600 transition-colors duration-200"
              aria-label="Facebook"
            >
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
                <path d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"/>
              </svg>
            </a>
            <a
              href="https://github.com/rubykachu"
              target="_blank"
              class="text-gray-400 hover:text-gray-900 transition-colors duration-200"
              aria-label="GitHub"
            >
              <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4" viewBox="0 0 24 24" fill="currentColor">
                <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .316.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
              </svg>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup>
function copyrightYears(from) {
  const currentYear = new Date().getFullYear()
  return from === currentYear ? `${from}` : `${from}-${currentYear}`
}
</script>
