<script>
	let email,
		password,
		confirmPassword = '';
</script>

<div class="flex flex-col items-center justify-center flex-1 p-24 max-w-400 max-h-400">
	<h1>Register</h1>
	<div class="w-10px p-10px">
		<label class="label">
			<span>Email</span>
			<input bind:value={email} class="w-full input" type="text" placeholder="Email" />
		</label>
		<label class="label">
			<span>Password</span>
			<input bind:value={password} class="w-full input" type="text" placeholder="Password" />
		</label>
		<label class="label">
			<span>Confirm Password</span>
			<input
				bind:value={confirmPassword}
				class="w-full input"
				type="text"
				placeholder="Confirm Password"
			/>
		</label>

		<button type="button" class="btn variant-filled-surface">Register Now</button>
	</div>
</div>
