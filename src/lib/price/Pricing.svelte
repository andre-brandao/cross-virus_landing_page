<script>
	import { wpp_link } from '../links';

	let feat1 = 'Cardapio de funcionalidades';
	let feat2 = 'Envio de Emails';
	let feat5 = 'Controle de Mesas';
	let feat3 = 'Relatorios ';
	let feat4 = 'Monitoramento';
</script>

<section class="bg-white dark:bg-gray-900">
	<div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16 lg:px-6">
		<div class="mx-auto max-w-screen-md text-center mb-8 lg:mb-12">
			<h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">
				Feito para prefeituras de todos os tamanhos
			</h2>
			<p class="mb-5 font-light text-gray-500 sm:text-xl dark:text-gray-400">
				Escolha o plano que melhor se encaixa com sua situação
			</p>
		</div>
		<div class="space-y-8 lg:grid lg:grid-cols-3 sm:gap-6 xl:gap-10 lg:space-y-0">
			<!-- Pricing Card -->
			<div
				class="flex flex-col p-6 mx-auto max-w-lg text-center text-gray-900 bg-white rounded-lg border border-gray-100 shadow dark:border-gray-600 xl:p-8 dark:bg-gray-800 dark:text-white"
			>
				<h3 class="mb-4 text-2xl font-semibold">Pequenas Cidades</h3>
				<p class="font-light text-gray-500 sm:text-lg dark:text-gray-400">
					Acesso Limitado, sem funcionalidades premium
				</p>
				<div class="flex justify-center items-baseline mt-8">
					<span class="mr-2 text-5xl font-extrabold">R$45</span>
					<span class="text-gray-500 dark:text-gray-400">/mes</span>
				</div>
				<span class="mb-8">/1.000 habitantes</span>

				<!-- List -->
				<ul role="list" class="mb-8 space-y-4 text-left">
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat1}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path>
						</svg>
						<span>{feat2}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>

						<span>{feat3}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>
						<span>{feat4} </span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>
						<span>{feat5}</span>
					</li>
				</ul>
				<a
					href={wpp_link}
					class="text-white bg-primary-600 hover:bg-primary-700 focus:ring-4 focus:ring-primary-200 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:text-white dark:focus:ring-primary-900"
					>Get started</a
				>
			</div>
			<!-- Pricing Card -->
			<div
				class="flex flex-col p-6 mx-auto max-w-lg text-center text-gray-900 bg-white rounded-lg border border-gray-100 shadow dark:border-gray-600 xl:p-8 dark:bg-gray-800 dark:text-white"
			>
				<h3 class="mb-4 text-2xl font-semibold">Cidades</h3>
				<p class="font-light text-gray-500 sm:text-lg dark:text-gray-400">
					Acesso as funcionalidades basicas do cardapio e suporte basico.
				</p>
				<div class="flex justify-center items-baseline mt-8">
					<span class="mr-2 text-5xl font-extrabold">R$4.500</span>
					<span class="text-gray-500 dark:text-gray-400">/mes</span>
				</div>
				<span class="mb-8">/100.000 habitantes</span>

				<!-- List -->
				<ul role="list" class="mb-8 space-y-4 text-left">
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat1}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat2}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>
						<span>{feat3} </span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>
						<span>{feat4} </span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-red-500 dark:text-red-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
						>
							<path
								fill-rule="evenodd"
								d="M6 6L14 14M14 6L6 14"
								stroke="currentColor"
								stroke-width="2"
							></path></svg
						>
						<span>{feat5}</span>
					</li>
				</ul>
				<a
					href={wpp_link}
					class="text-white bg-primary-600 hover:bg-primary-700 focus:ring-4 focus:ring-primary-200 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:text-white dark:focus:ring-primary-900"
					>Get started</a
				>
			</div>
			<!-- Pricing Card -->
			<div
				class="flex flex-col p-6 mx-auto max-w-lg text-center text-gray-900 bg-white rounded-lg border border-gray-100 shadow dark:border-gray-600 xl:p-8 dark:bg-gray-800 dark:text-white"
			>
				<h3 class="mb-4 text-2xl font-semibold">Metropoles</h3>
				<p class="font-light text-gray-500 sm:text-lg dark:text-gray-400">
					Acesso as funcionalidades basicas do cardapio e suporte basico.
				</p>
				<div class="flex justify-center items-baseline mt-8">
					<span class="mr-2 text-5xl font-extrabold">R$45.000</span>
					<span class="text-gray-500 dark:text-gray-400">/mes</span>
				</div>
				<span class="mb-8">/1.000.000 habitantes</span>

				<!-- List -->
				<ul role="list" class="mb-8 space-y-4 text-left">
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat1}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat2}</span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat3} </span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat4} </span>
					</li>
					<li class="flex items-center space-x-3">
						<!-- Icon -->
						<svg
							class="flex-shrink-0 w-5 h-5 text-green-500 dark:text-green-400"
							fill="currentColor"
							viewBox="0 0 20 20"
							xmlns="http://www.w3.org/2000/svg"
							><path
								fill-rule="evenodd"
								d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z"
								clip-rule="evenodd"
							></path></svg
						>
						<span>{feat5}</span>
					</li>
				</ul>
				<a
					href={wpp_link}
					class="text-white bg-primary-600 hover:bg-primary-700 focus:ring-4 focus:ring-primary-200 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:text-white dark:focus:ring-primary-900"
					>Get started</a
				>
			</div>
		</div>
	</div>
</section>
