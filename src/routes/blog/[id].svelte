<script context="module">
    export const load = async ({ fetch, params }) => {
        const { id } = params

        const res = await fetch(`https://jsonplaceholder.typicode.com/posts/${id}`);
        const post = await res.json();

        return {
            props: {
                post,
            }
        }
    }
</script>

<script>
    export let post;
</script>

<div class="container">
    <h1>
        ${post.body}
    </h1>
</div>