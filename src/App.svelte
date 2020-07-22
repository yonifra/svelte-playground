<script>
  let name = "world";

  const calculate = () => {
    for (let i = 0; i < 20; i++) {
      world += i;
    }

    return world;
  };
</script>

<h1>Hello {calculate}! How are you?</h1>
