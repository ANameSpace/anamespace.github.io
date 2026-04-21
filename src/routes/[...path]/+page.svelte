<script>
  import { page } from '$app/state';
</script>

<main style="text-align: center; padding: 4rem;">
  <h1>404</h1>
  <p>Страница <strong>{page.url.pathname}</strong> не найдена</p>
  <a href="/">← Вернуться на главную</a>
</main>