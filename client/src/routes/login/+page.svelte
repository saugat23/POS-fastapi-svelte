<script>
import logo from "../../../static/login/login-bg.png"
</script>

<svelte:head>
    <title>POS Login</title> 
</svelte:head>

<div class="min-h-full h-screen w-screen flex justify-center items-center bg-linear-to-r from-[#1c4f4a] to-bg-stone-100 text-xs text-white">
	<div class="bg-stone-100 border-3 border-solid border-[#1c4f4a] min-h-96 min-w-96 w-auto h-auto flex rounded-2xl">
		<div class="bg-stone-100 w-1/2 h-full min-h-96 rounded-l-2xl flex justify-center items-center">
			<img src="/login/login-bg.png" class="w-full h-full rounded-2xl" alt="Login bg" />
		</div>
		<form class="bg-[#1c4f4a] w-1/2 h-full min-h-96 rounded-r-2xl flex flex-col justify-center items-center p-8 space-y-5">
			<h3 class="text-4xl text-black text-white self-start">Login</h3>
			<input type="email" name="email" id="email" placeholder="Email address" class="w-full p-2 rounded-lg border-1 border-solid border-stone-100 outline-none" />
<input type="password" name="password" id="password" placeholder="Password" class="w-full p-2 rounded-lg border-1 border-solid border-stone-100 outline-none" />
			<button type="submit" class="bg-[#fc6719] hover:bg-white hover:text-[#fc6719] text-extrabold text-base p-2 rounded-lg w-full">Log in</button>
			<a href="#" class="text-[#fc6719] text-xs">Forgot your password?</a>
		</form>
	</div>
</div>


<style lang="postcss">
@reference "tailwindcss";
</style>
