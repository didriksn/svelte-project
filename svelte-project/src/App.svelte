<script>
	let nums = {
		1 : 1,
		2 : 2,
		3 : 3,
		4 : 4,
		5 : 5,
		6 : 6,
		7 : 7,
		8 : 8,
		9 : 9,
		0 : 0
	}

	const one = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[1]
		document.body.appendChild(swer)
		swer
	}
	const two = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[2]
		document.body.appendChild(swer)
		swer
	}
	const three = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[3]
		document.body.appendChild(swer)
		swer
	}
	const four = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[4]
		document.body.appendChild(swer)
		swer
	}
	const five = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[5]
		document.body.appendChild(swer)
		swer
	}
	const six = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[6]
		document.body.appendChild(swer)
		swer
	}
	const seven = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[7]
		document.body.appendChild(swer)
		swer
	}
	const eight = () => {
		let swer = document.createElement("div");
		swer.innerText = nums[8]
		document.body.appendChild(swer)
		swer;
	}
	const nine = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[9]
		document.body.appendChild(swer)
		swer
	}
	const zero = () => {
		let swer = document.createElement("div")
		swer.innerText = nums[0]
		document.body.appendChild(swer)
		swer
	}
</script>

<main>
	<button on:click={one}>
		{nums[1]}
	</button>
	<button on:click={two}>
		{nums[2]}
	</button>
	<button on:click={three}>
		{nums[3]}
	</button>
	<button on:click={four}>
		{nums[4]}
	</button>
	<button on:click={five}>
		{nums[5]}
	</button>
	<button on:click={six}>
		{nums[6]}
	</button>
	<button on:click={seven}>
		{nums[7]}
	</button>
	<button on:click={eight}>
		{nums[8]}
	</button>
	<button on:click={nine}>
		{nums[9]}
	</button>
	<button on:click={zero}>
		{nums[0]}
	</button>
</main>